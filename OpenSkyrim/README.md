# OpenSkyrim
A free mixin-based injection hacked-client using Minecraft Forge based on LiquidBounce for HuaYuTing server, supporting version 1.12.2.


## Issues
If you notice any bugs or missing features, you can let us know by opening an issue [here](https://github.com/PaimonMinecraft/OpenSkyrim/issues).

## License
This project is subject to the [GNU General Public License v3.0](LICENSE). This does only apply for source code located directly in this clean repository. During the development and compilation process, additional source code may be used to which we have obtained no rights. Such code is not covered by the GPL license.

For those who are unfamiliar with the license, here is a summary of its main points. This is by no means legal advice nor legally binding.

You are allowed to
- use
- share
- modify

this project entirely or partially for free and even commercially. However, please consider the following:

- **You must disclose the source code of your modified work and the source code you took from this project. This means you are not allowed to use code from this project (even partially) in a closed-source (or even obfuscated) application.**
- **Your modified application must also be licensed under the GPL** 

禁止魔改并付费发布，一经发现后果自负。

Do the above and share your source code with everyone; just like we do.

## Setting up a Workspace
LiquidBounce is using Gradle, so make sure that it is installed properly. Instructions can be found on [Gradle's website](https://gradle.org/install/).
1. Clone the repository using `git clone https://github.com/Paim0nMinecraft/OpenSkyrim/`. 
2. CD into the local repository folder.
3. Switch to the legacy branch using `git checkout legacy`
4. Depending on which IDE you are using execute either of the following commands:
    - For IntelliJ: `gradlew --debug setupDevWorkspace idea genIntellijRuns build`
    - For Eclipse: `gradlew --debug setupDevWorkspace eclipse build`
5. Open the folder as a Gradle project in your IDE.
6. Select either the Forge or Vanilla run configuration.

## Additional libraries
### Mixins
Mixins can be used to modify classes at runtime before they are loaded. LiquidBounce is using it to inject its code into the Minecraft client. This way, we do not have to ship Mojang's copyrighted code. If you want to learn more about it, check out its [Documentation](https://docs.spongepowered.org/5.1.0/en/plugin/internals/mixins.html).