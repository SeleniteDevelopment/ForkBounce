# SkidBounce
A free mixin-based injection hacked-client for Minecraft using Minecraft Forge, supporting version 1.8.9.

[Repository link](https://github.com/ManInMyVan/SkidBounce) | [Source code archive](SkidBounce-main.zip)

## Versions
- [0.1.0](skidbounce-v0.1.0.jar)
- [0.1.1](skidbounce-v0.1.1.jar)

# Clients to skid
[LiquidBounce](https://github.com/CCBlueX/LiquidBounce/tree/legacy)\
[FDPClient](https://github.com/SkidderMC/FDPClient)\
[NightX](https://github.com/Aspw-w/NightX-Client)\
[CrossSine](https://github.com/shxp3/CrossSine)\
[LiquidBouncePlus-Reborn](https://github.com/liquidbounceplusreborn/LiquidbouncePlus-Reborn)

## Completion
as of latest commit
|      Thing       |   Completion    |
|:----------------:|:---------------:|
|      NoSlow      | :yellow_circle: |
|      NoWeb       | :green_circle:  |
|      Speed       | :yellow_circle: |
|     LongJump     |  :red_circle:   | 
|       Fly        | :yellow_circle: | 
|      NoFall      | :yellow_circle: | 
|       Hud        |  :red_circle:   | 
|    Animations    |  :red_circle:   | 
|      Jesus       |  :red_circle:   | 
|     Disabler     | :yellow_circle: |
|      Phase       |  :red_circle:   | 
|     Velocity     |  :red_circle:   | 
|     ClickGUI     |  :red_circle:   | 
|    AutoBlock     |  :red_circle:   | 
|     Modules      |  :red_circle:   | 
|     Scaffold     |  :red_circle:   | 
|      Tower       |  :red_circle:   | 
|       Step       |  :red_circle:   | 
|    Criticals     |  :red_circle:   | 
|     AntiVoid     |  :red_circle:   | 
|    FastClimb     |  :red_circle:   | 
| InventoryManager |  :red_circle:   | 
|      Spider      |  :red_circle:   | 
|     FastUse      |  :red_circle:   | 
| Everything Else  |  :red_circle:   | 
## Issues
If you notice any bugs or missing features, you can let us know by opening an issue [here](https://github.com/ManInMyVan/SkidBounce/issues).

## License
This project is subject to the GNU General Public License v3.0. This does only apply for source code located directly in this clean repository. During the development and compilation process, additional source code may be used to which we have obtained no rights. Such code is not covered by the GPL license.

For those who are unfamiliar with the license, here is a summary of its main points. This is by no means legal advice nor legally binding.

You are allowed to
- use
- share
- modify

this project entirely or partially for free and even commercially. However, please consider the following:

- **You must disclose the source code of your modified work and the source code you took from this project. This means you are not allowed to use code from this project (even partially) in a closed-source (or even obfuscated) application.**
- **Your modified application must also be licensed under the GPL** 

Do the above and share your source code with everyone; just like we do.

## Setting up a Workspace
LiquidBounce is using Gradle, so make sure that it is installed properly. Instructions can be found on [Gradle's website](https://gradle.org/install/).
1. Clone the repository using `git clone https://github.com/ManInMyVan/SkidBounce/`. 
2. CD into the local repository folder.
3. Depending on which IDE you are using execute either of the following commands:
    - For IntelliJ: `gradlew --debug setupDevWorkspace idea genIntellijRuns build`
    - For Eclipse: `gradlew --debug setupDevWorkspace eclipse build`
4. Open the folder as a Gradle project in your IDE.
5. Select either the Forge or Vanilla run configuration.

## Additional libraries
### Mixins
Mixins can be used to modify classes at runtime before they are loaded. SkidBounce is using it to inject its code into the Minecraft client. This way, we do not have to ship Mojang's copyrighted code. If you want to learn more about it, check out its [Documentation](https://docs.spongepowered.org/5.1.0/en/plugin/internals/mixins.html).

## Contributing

We appreciate contributions. So if you want to support us, feel free to make changes to SkidBounce's source code and submit a pull request. Currently, our main goals are the following:
1. Improve SkidBounce's performance.
2. Re-work most of the render code.

If you have experience in one or more of these fields, we would highly appreciate your support.