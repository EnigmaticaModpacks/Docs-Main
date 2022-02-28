# OptiFine

OptiFine is a mod for Minecraft clients intended to add a number of new graphics options to the game as well as add support for shader packs. In some cases it can also increase performance considerably, although this will vary depending on your hardware. We generally find that adding OptiFine results in higher memory usage but lower CPU and GPU usage.

## Installing OptiFine

You can add it to the pack by downloading the correct version of OptiFine and placing the .jar file in the mods folder alongside other mods.

Please note: OptiFine should never be added to a server (and will indeed crash the server). It is a client-side mod only.

Depending on the launcher you are using, there will be a different method to find the mods folder.

### CurseForge Client & GDLauncher

1. Right-click on the modpack, then select Open Folder.
2. Double-click on the mods folder, and put the OptiFine.jar in there.

### MultiMC

1. Right-click on the modpack, then select Minecraft Folder.
2. Double-click on the mods folder, and put the OptiFine.jar in there.

## Installing Shader Packs

Note: Shader packs should be switched before loading a Minecraft world or connecting to a multiplayer server, from the title screen.

1. From the Enigmatica Title Screen, click on Options, then Video Settings, then Shaders, then click the Shaders folders button at the bottom.
2. Download the shader pack you wish to use. We have included links to several shader packs below, but this is by no means an exhaustive list.
3. Place the downloaded shader pack in the newly opened window showing the shaderpacks folder.
4. Select the shader pack from the list in the in-game menu.

### Sildur's Shaders

Sildur's shaders come in a variety of levels - Lite, Medium, High, High w/ Motion Blur, Extreme, and Extreme w/ Volumetric Lighting. The range of packs available ensure that there's something for everybody.

{% hint style="info" %}
To remove the horizontal line in the skybox you have to disable Astral Sorcery's custom skybox, by removing "minecraft:overworld" from skyRenderingEnabled at astralsorcery-client.toml in the config directory.
{% endhint %}

:link:[Website](https://sildurs-shaders.github.io)\
:inbox\_tray:[Download](https://sildurs-shaders.github.io/downloads/)

### BSL Shaders

BSL Shaders are great for survival Minecraft, with a focus on optimisation and customisation. They achieve a balance between looking good, performing well, and having subtle effects that don't detract from playing the game.

:link:[Website](https://bitslablab.com/bslshaders)\
:inbox\_tray:[Download](https://bitslablab.com/bslshaders/#download)

### Complementary Shaders

Complementary Shaders were originally based on BSL Shaders, but the developer has shifted focus towards compatibility with as many different hardware and mod configurations as possible, and has deviated considerably from the starting point of BSL shaders, resulting in quite a different end result.

Please note that Complementary Shaders also includes a resource pack, so installation is slightly different to other shaders. We recommend reading through the CurseForge page for the shader pack before installing it.

:link:[CurseForge Page](https://www.curseforge.com/minecraft/customization/complementary-shaders)\
:inbox\_tray:[Download](https://www.curseforge.com/minecraft/customization/complementary-shaders/download/3156158)

## Warnings / Disclaimer

Most mod developers will not guarantee OptiFine support since OptiFine changes a lot of expected Minecraft functionality and is additionally not an open source mod, causing it to be more difficult to achieve compatibility with. Many developers will avoid fixing problems that only occur with OptiFine installed and will close issue reports that include OptiFine. Because of this, you may experience missing textures or models, crashes, visual glitches, or negative performance while using OptiFine. While we have included the installation steps here and we will attempt to help you, we promise no support beyond this wiki page because of this. If you are seeking support on our [Discord server](https://valhelsia.net/discord) for help with a crash or bug, please remove OptiFine (and OptiForge, if added) before asking for help and submitting a crash report.
