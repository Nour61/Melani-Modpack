
## Introduction

You will need Fabric to make use of this obviously, you can get it from here: https://fabricmc.net/use/

Table of contents:
- [Mod list](https://github.com/Alejandro-Sosa/Melani-Modpack#mod-list)
- [Java & JVM Flags](https://github.com/Alejandro-Sosa/Melani-Modpack#java--jvm-flags)
- [Optional steps](https://github.com/Alejandro-Sosa/Melani-Modpack#optional-steps)

Current version of this modpack is focused on Minecraft 1.16.5

## Mod list

The main attraction, behold my mighty list! You can download the latest version from the [releases](https://github.com/Alejandro-Sosa/Melani-Modpack/releases) as an alternative simply click on the name of each mod to download it.

*The symbol ⚠️ means could cause issues in some specific use cases. I personally use them and deem them safe but not everyone plays the same.*

### Performance

- [Sodium](https://github.com/CaffeineMC/sodium-fabric/suites/2359795839/artifacts/49961006) - One of the biggest mods to help, optimizes general rendering.
- [Sodium Extra](https://github.com/FlashyReese/sodium-extra-fabric/suites/2363742178/artifacts/50058653) - A expansion for Sodium which adds a bunch more toggles.
- [Starlight](https://github.com/Spottedleaf/Starlight/releases/download/1.0.0-RC1/starlight-fabric-1.0.0-RC1-1.16.x.jar) - A rewrite of the lightning engine that is considerably faster.
- [Lithium](https://github.com/CaffeineMC/lithium-fabric/suites/2240511832/artifacts/46509597) - Smaller optimizations but anything is welcome.
-  ⚠️ [Lazydfu](https://ci.velocitypowered.com/job/lazydfu/12/artifact/build/libs/lazydfu-0.1.3-SNAPSHOT.jar) - If the DataFixerUpper finished his school this is the result. Loading times are heavily improved.
- [Krypton](https://ci.velocitypowered.com/job/krypton/lastSuccessfulBuild/artifact/build/libs/krypton-0.1.3-SNAPSHOT.jar) - Mainly for the server itself but can provide small use for the client aswell.
- [FastChest](https://www.curseforge.com/minecraft/mc-mods/fastchest/download/3222361/file) - Makes the chests a static block, powerful help with huge storage rooms full of chests.
-  ⚠️ [Entity Culling](https://github.com/tr7zw/EntityCulling-Fabric/suites/2372836291/artifacts/50320558) - Experimental but can help with big farms or lobbies full of players. Can't hurt to try right?
- [Dynamic FPS](https://github.com/juliand665/Dynamic-FPS/releases/download/2.0.1/dynamic-fps-2.0.1.jar) - Whenever the game is unfocused it puts less work in.
- [NoFade](https://github.com/UltimateBoomer/mc-no-fade/suites/2194499442/artifacts/45274069) - Simply removes the fade from the Mojang splash screen, small but effective.
-  ⚠️ [FerriteCore](https://www.curseforge.com/minecraft/mc-mods/ferritecore-fabric/download/3253564/file) - Focuses at reducing ram usage. Have yet to run into issues but still, you are warned.
-  [BetterBeds](https://github.com/TeamMidnightDust/BetterBeds/releases/download/v1.1.0/betterbeds-1.1.0.jar) - Optimizes beds, that's it.

### Functionality (Required)

- [Fabric API](https://www.curseforge.com/minecraft/mc-mods/fabric-api/download/3248105/file) - A requirement for everything. You have to install this for everything to work.
- [Modmenu](https://github.com/TerraformersMC/ModMenu/suites/2099345544/artifacts/42641822) - A handy mod for organizing and configuration.
- [Notenoughcrashes](https://www.curseforge.com/minecraft/mc-mods/not-enough-crashes/download/3226331/file) - Useful tool for crashes and doesn't kill the game when it does.

### Tools & Beauty (Optional)

❕ *These mods have a good use but don't contribute towards the main goal; ultimate performance. You can choose to use them or just skip it altogether. These are not included in releases and all mods are full clientside only*

- [Ok Zoomer](https://github.com/joaoh1/OkZoomer/releases/download/4.0.1%2B1.16.2/okzoomer-4.0.1+1.16.2.jar) - Allows you to zoom in.

## Java & JVM Flags

A particularly crucial step, here is how-to:

**Installing the latest Java version**
- Step 1: Download Java 16 from https://github.com/AdoptOpenJDK/openjdk16-binaries/releases/download/jdk-16%2B36/OpenJDK16-jre_x64_windows_hotspot_16_36.msi
- Step 2: Run the installer and complete it
- Step 3: Now open the Minecraft launcher and edit your Fabric profile
- Step 4: Select below "More options"
- Step 5: See Java Executable and click on browse
- Step 6: Now find the file javaw in the following directory: C:\Program Files\AdoptOpenJDK\jre-16.0.0.36-hotspot\bin
- Step 7: Select the file and click on save
- Step 8: And you are done, should give a solid improvement in stability and performance

⚠️ *Please note some mods tend to break on the latest, all the mods from my modpack will work with it but if it does not work with any of your own added mods try Java 11 instead.*

**JVM Flags**
- Coming soon, this is something i myself haven't fully figured out. Default is good enough in most use cases.
- For now this should be a good read: https://gist.github.com/jellysquid3/8a7b21e57f47f5711eb5697e282e502e

## Optional steps

Still low on FPS? This corner is reserved for the perfectionist or the one on a low budget. (Still a work-in-progress, feel free to PR any tips for performance 😉)

**Clean up your machine**
- Remove anything unwanted and kill everything that is running, pretty straight forward right.
