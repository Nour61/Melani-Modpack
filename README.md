
## Introduction

Melani Modpack is a collection of mods purely focused on performance. 

You will need Fabric to make use of this, you can get it from here: https://fabricmc.net/use/

Table of contents:
- [Mod list](https://github.com/Alejandro-Sosa/Melani-Modpack#mod-list)
  - [Performance](https://github.com/Alejandro-Sosa/Melani-Modpack#performance)
  - [Functionality (Required)](https://github.com/Alejandro-Sosa/Melani-Modpack#functionality-required)
  - [Utility (Optional)](https://github.com/Alejandro-Sosa/Melani-Modpack#utility-optional)
  - [Prettiness (Optional)](https://github.com/Alejandro-Sosa/Melani-Modpack#prettiness-optional)
- [Java & JVM Flags](https://github.com/Alejandro-Sosa/Melani-Modpack#java--jvm-flags)
- [Optional steps](https://github.com/Alejandro-Sosa/Melani-Modpack#optional-steps)

## Mod list

* Downloads can be found at [Releases](https://github.com/Alejandro-Sosa/Melani-Modpack/releases). Alternatively you can click on the download button to download the latest version of the mod. Click on the name of the mod to get redirected to the source page. All mods are client-side and don't require the server to have it installed.

* Current version of this modpack is focused on Minecraft 1.16.5.

The main attraction, behold my mighty list! 🌩️ *Updated weekly, last updated at 04/04/2021*

### Performance

- [Sodium](https://github.com/CaffeineMC/sodium-fabric) [![Sodium](https://img.shields.io/badge/-%E2%86%93-brightgreen)](https://github.com/CaffeineMC/sodium-fabric/suites/2359795839/artifacts/49961006) - One of the biggest mods to help, optimizes general rendering.
  - [Sodium Extra](https://github.com/FlashyReese/sodium-extra-fabric) [![SodiumExtra](https://img.shields.io/badge/-%E2%86%93-brightgreen)](https://github.com/FlashyReese/sodium-extra-fabric/suites/2419690529/artifacts/51602270) - A expansion for Sodium which adds a bunch more toggles.
- [Starlight](https://github.com/Spottedleaf/Starlight) [![Starlight](https://img.shields.io/badge/-%E2%86%93-brightgreen)](https://github.com/Spottedleaf/Starlight/releases/download/1.0.0-RC1/starlight-fabric-1.0.0-RC1-1.16.x.jar) - A rewrite of the lightning engine that is considerably faster.
- [Lithium](https://github.com/CaffeineMC/lithium-fabric) [![Lithium](https://img.shields.io/badge/-%E2%86%93-brightgreen)](https://github.com/CaffeineMC/lithium-fabric/suites/2240511832/artifacts/46509597) - Smaller optimizations but anything is welcome.
-  ⚠️ [LazyDFU](https://github.com/astei/lazydfu) [![LazyDFU](https://img.shields.io/badge/-%E2%86%93-brightgreen)](https://ci.velocitypowered.com/job/lazydfu/13/artifact/build/libs/lazydfu-0.1.3-SNAPSHOT.jar) - If the DataFixerUpper finished his school this is the result. Loading times are heavily improved.
- [Krypton](https://github.com/astei/krypton) [![LazyDFU](https://img.shields.io/badge/-%E2%86%93-brightgreen)](https://ci.velocitypowered.com/job/krypton/53/artifact/build/libs/krypton-0.1.3-SNAPSHOT.jar) - Mainly for the server itself but can provide small use for the client in addition.
- [Enhanced Block Entities](https://modrinth.com/mod/ebe) [![EBE](https://img.shields.io/badge/-%E2%86%93-brightgreen)](https://cdn.modrinth.com/data/OVuFYfre/versions/0.1/enhancedblockentities-0.1--1.16.x.jar) - Makes the chests a static block, powerful help with huge storage rooms full of chests.
-  ⚠️ [Entity Culling](https://www.curseforge.com/minecraft/mc-mods/entityculling) [![EntityCulling](https://img.shields.io/badge/-%E2%86%93-brightgreen)](https://github.com/tr7zw/EntityCulling-Fabric/suites/2414179978/artifacts/51463326) - Experimental but can help with big farms or lobbies full of players. Can't hurt to try right?
- [Dynamic FPS](https://modrinth.com/mod/dynamic-fps) [![DynamicFPS](https://img.shields.io/badge/-%E2%86%93-brightgreen)](https://github.com/juliand665/Dynamic-FPS/releases/download/2.0.1/dynamic-fps-2.0.1.jar) - Whenever the game is unfocused it puts less work in.
- [NoFade](https://modrinth.com/mod/no-fade) [![NoFade](https://img.shields.io/badge/-%E2%86%93-brightgreen)](https://github.com/UltimateBoomer/mc-no-fade/suites/2194499442/artifacts/45274069) - Simply removes the fade from the Mojang splash screen, small but effective.
-  ⚠️ [FerriteCore](https://github.com/malte0811/FerriteCore) [![FerriteCore](https://img.shields.io/badge/-%E2%86%93-brightgreen)](https://www.curseforge.com/minecraft/mc-mods/ferritecore-fabric/download/3253564/file) - Focuses at reducing ram usage. Have yet to run into issues but still, you are warned.
-  [BetterBeds](https://modrinth.com/mod/better-beds) [![BetterBeds](https://img.shields.io/badge/-%E2%86%93-brightgreen)](https://github.com/TeamMidnightDust/BetterBeds/releases/download/v1.1.0/betterbeds-1.1.0.jar) - Optimizes beds, that's it.
-  [CullLeaves](https://modrinth.com/mod/cull-leaves) [![CullLeaves](https://img.shields.io/badge/-%E2%86%93-brightgreen)](https://github.com/TeamMidnightDust/CullLeaves/releases/download/v2.0.0/cullleaves-2.0.0.jar) - Makes leaves more transparent providing a increase in framerate.
-  [Retro Items](https://modrinth.com/mod/retroitems) [![RetroItems](https://img.shields.io/badge/-%E2%86%93-brightgreen)](https://github.com/hatninja/RetroItems/suites/2383435139/artifacts/50617931) - Items are rendered more simple, improving performance.
-  ⚠️ [Hydrogen](https://github.com/CaffeineMC/hydrogen-fabric) [![Hydrogen](https://img.shields.io/badge/-%E2%86%93-brightgreen)](https://github.com/CaffeineMC/hydrogen-fabric/suites/1850578525/artifacts/35880030) - Mod that reduces memory usage, experimental.

*The symbol ⚠️ means could cause issues in some specific use cases. I personally use them and deem them safe but not everyone plays the same.*

### Functionality (Required)

- [Fabric API](https://www.curseforge.com/minecraft/mc-mods/fabric-api) [![FabricAPI](https://img.shields.io/badge/-%E2%86%93-brightgreen)](https://www.curseforge.com/minecraft/mc-mods/fabric-api/download/3248105/file) - A requirement for everything. You have to install this for everything to work.
- [Modmenu](https://github.com/TerraformersMC/ModMenu) [![Modmenu](https://img.shields.io/badge/-%E2%86%93-brightgreen)](https://github.com/TerraformersMC/ModMenu/suites/2099345544/artifacts/42641822) - A handy mod for organizing and configuration.
- [Indium](https://github.com/comp500/Indium) [![Indium](https://img.shields.io/badge/-%E2%86%93-brightgreen)](https://github.com/comp500/Indium/suites/2363754187/artifacts/50058978) - Requirement for Enhanced Block Entities.
- [Notenoughcrashes](https://www.curseforge.com/minecraft/mc-mods/not-enough-crashes) [![Notenoughcrashes](https://img.shields.io/badge/-%E2%86%93-brightgreen)](https://www.curseforge.com/minecraft/mc-mods/not-enough-crashes/download/3226331/file) - Useful tool for crashes and doesn't kill the game when it does.

### Utility (Optional)

❕ *These mods have a good use but don't contribute towards the main goal; ultimate performance. You can choose to use them or just skip it altogether. These are not included in releases and all mods are full clientside only*

- [Ok Zoomer](https://modrinth.com/mod/ok-zoomer) [![OkZoomer](https://img.shields.io/badge/-%E2%86%93-brightgreen)](https://github.com/joaoh1/OkZoomer/releases/download/4.0.1%2B1.16.2/okzoomer-4.0.1+1.16.2.jar) - Allows you to zoom in.

### Prettiness (Optional)

❕ *Mods that will impact performance but will make your game a bit more prettier, not included in releases and all mods are clientside only.*

- [Falling Leaves](https://modrinth.com/mod/fallingleaves) [![FallingLeaves](https://img.shields.io/badge/-%E2%86%93-brightgreen)](https://github.com/RandomMcSomethin/fallingleaves/suites/2409365867/artifacts/51323158) - Pretty leaves falling from leaves, a very nice touch to worlds.

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
- Physically clean your PC! Remove any dust or other foreign items from inside and make sure it has good airflow.
