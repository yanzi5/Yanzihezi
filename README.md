Hello Minecraft! Launcher Build Status
Join chat! Discord KaiHeiLa

Introduction
HMCL is a Minecraft launcher which supports Mod management, game customizing, auto installing(Forge, LiteLoader and OptiFine), modpack creating, UI customizing and so on.

No plugin API is provided.

Download
Download the latest version from the official website

Note: The recent versions in Github release is the beta version, which contains extra testing functions compared to the release versions on the official website. However, they may be unstable and you're more likely to encounter bugs or unexpected problems.

If not necessary, it is recommended to download the ones from the official website.

License
The software is distributed under GPL v3 with additional terms.

Additional terms under GPLv3 Section 7
When you distribute a modified version of the software, you must change the software name or the version number in a reasonable way in order to distinguish it from the original version. [under GPLv3, 7(c).]

The software name and the version number can be edited here.

You must not remove the copyright declaration displayed in the software. [under GPLv3, 7(b).]

Chinese Translation:

附加条款（依据 GPLv3 协议第七条）
当你分发本程序的修改版本时，你必须以一种合理的方式修改本程序的名称或版本号，以示其与原始版本不同。[依据 GPLv3, 7(c).]

本程序的名称及版本号可在此处修改。

你不得移除本程序所显示的版权声明。[依据 GPLv3, 7(b).]

Contribution
If you want to submit a pull request, there're some requirements:

IDE: Intellij IDEA.
Compiler: Java 1.8.
Do NOT modify gradle files.
Compilation
Simply execute following command:

./gradlew clean build
Make sure you have Java installed with JavaFX 8 at least. Liberica full JDK 8 or later is recommended.

JVM Options (for debugging)
Parameter	Description
-Dhmcl.self_integrity_check.disable=true	Bypass the self integrity check when checking for update.
-Dhmcl.bmclapi.override=<version>	Override api root of BMCLAPI download provider, defaults to https://bmclapi2.bangbang93.com. e.g. https://download.mcbbs.net.
-Dhmcl.font.override=<font family>	Override font family.
-Dhmcl.version.override=<version>	Override the version number.
-Dhmcl.update_source.override=<url>	Override the update source.
-Dhmcl.authlibinjector.location=<path>	Use specified authlib-injector (instead of downloading one).
-Dhmcl.openjfx.repo=<maven repository url>	Add custom maven repository for download OpenJFX.
-Dhmcl.native.encoding=<encoding>	Override the native encoding.
-Dhmcl.microsoft.auth.id=<App ID>	Override Microsoft OAuth App ID.
-Dhmcl.microsoft.auth.secret=<App Secret>	Override Microsoft OAuth App secret.
