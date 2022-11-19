<div align="center">

# Prismarine
[![License](https://img.shields.io/github/license/PurpurMC/Purpur)](LICENSE.md)
[![Build Prismarine](https://img.shields.io/github/workflow/status/PrismarineTeam/Prismarine/Build%20Prismarine)](https://github.com/PrismarineTeam/Prismarine/actions/workflows/build.yml)
[![Upstream Prismarine](https://img.shields.io/github/workflow/status/PrismarineTeam/PrismarineManager/Scheduled%20Upstream%20(1.19.2)?label=upstream)](https://github.com/PrismarineTeam/PrismarineManager/actions/workflows/prismarine.yml)

[:kr: Korean](src/README/KOR.md) | **:us: English**

A Server Platform for Minecraft: Java Edition with many improvements based on [Paper](https://github.com/PaperMC/Paper)

*You can support this project through Sponsor at right (or bottom)!*

</div>

## Features
- Based on [Bukkit](https://hub.spigotmc.org/stash/projects/SPIGOT/repos/bukkit/browse), [CraftBukkit](https://hub.spigotmc.org/stash/projects/SPIGOT/repos/craftbukkit/browse), [Spigot](https://hub.spigotmc.org/stash/projects/SPIGOT/repos/spigot/browse) and [Paper](https://github.com/PaperMC/Paper). Most plugins are fully supported and stable.
- Fast speed and wide api support, including all patches from [Pufferfish](https://github.com/pufferfish-gg/Pufferfish) and [Purpur](https://github.com/PurpurMC/Purpur).
- Multiple improvements and bug fixes are implemented by porting multiple mods.
- Have a better performance beacuse we removed unstable, old and optimized for particular users and only ported neccesary parts such as [Patina](https://github.com/PatinaMC/Patina), [JettPack](https://gitlab.com/Titaniumtown/JettPack), [EmpireCraft](https://github.com/starlis/EmpireCraft), [Akarin](https://github.com/Akarin-project/Akarin), [Slice](https://github.com/Cryptite/Slice), [Petal](https://github.com/bloom-host/Petal).
- Improve quality of server by porting patches disappeared or remained as a PR.
   - Ported patches can be found at [here](src/PORTED_PATCHES/ENG.md) 
- Provides the fastest upstream by using GitHub Action which do upstream automatically.
- Ability to disable Chat Report System.

## Downloads
[![Build Prismarine](https://img.shields.io/github/workflow/status/PrismarineTeam/Prismarine/Build%20Prismarine)](https://github.com/PrismarineTeam/Prismarine/releases/tag/latest)

In normal case, you can download latest JAR file by clicking [this](https://github.com/PrismarineTeam/Prismarine/releases/download/latest/Prismarine-paperclip-1.19.2-R0.1-SNAPSHOT-reobf.jar)

Mojmap or Bundler Jar can be downloaded [right side(or below)'s Releases tab](https://github.com/PrismarineTeam/Prismarine/releases/tag/latest).

## Communicate [<img src="https://github.com/intergrav/devins-badges/blob/v2/assets/minimal/social/twitter-singular_64h.png?raw=true" width="20px"></img>](https://twitter.com/TeamPrismarine)
[<img src="https://discord.com/api/guilds/781822976773455882/widget.png?style=banner3"></img>](https://discord.gg/kkqMSEVVxN)
[<img src="https://discord.com/api/guilds/1003295972203429949/widget.png?style=banner3"></img>](https://discord.gg/CQGVqeXQQC)

Join [Discord](https://discord.gg/CQGVqeXQQC) and let us know error and help us find how to solve it!

### Useful servers
- [Minecraft Development Dictionary (MDD)](https://discord.gg/AZwXTA9Pgx) (KOREAN)
   - You can get infos about Minecraft's news, announcement and server develop.

- [Minecraft Customization Community (MCC)](https://discord.gg/nnkecH6n24) (KOREAN)
   - You can get infos about Minecraft's mods, resource pack, shader.

## [#saveminecraft](https://saveminecraft.org/)
[#saveminecraft](https://saveminecraft.org/) is movement that refuses chatting report which added by Mojang Studios and Microsoft in Minecraft: Java Edition's 1.19.1(A.K.A. 1.**19.84**). #saveminecraft movement's goal is adding new permission for server admin without make minecraft's multiplay in danger, or removing chatting report. #saveminecraft movement protest peacefully and share this recognition widely. **You can view detail by clicking [here](src/SAVEMINECRAFT/ENG.md).**

Prismarine support this movement, not removing chatting report function which put minecraft's multiplay in danger, but make new permission for server admin.

Prismarine is developed for server admin to enable or disable chatting report function.
It's basically enabled, but if you want to disable, you can disable it in `prismarine.yml`. (Function provider: [No Chat Reports](https://modrinth.com/mod/no-chat-reports))

### Participate in #saveminecraft movement 
Please participate in [Change.org petition](https://chng.it/4MQX8YybMf). No register needs.

Please join [#saveminecraft movement Discord](https://discord.gg/saveminecraft).

Leave your opinion [in here](https://saveminecraft.org/opinions). You need Google account or GitHub account.

And, please spread this movement widely. Please help chatting report function removed.

## Configuration & Optimize
See [Wiki](https://github.com/PrismarineTeam/Prismarine/wiki)

## For Developers
### Requirements
You needs latest Git, JDK upper than 17.

Git should set `user.email` and `user.name`

If you want to set, use these commands in your terminal.
```bash
git config --global user.email "<your GitHub E-mail>"
git config --global user.name "<your GitHub ID>"
```

### Initial Setup
First, launch these commands in directory which you want to copy project.
```bash
git clone -b ver/1.19.2 https://github.com/PrismarineTeam/Prismarine
```
If project is copied or you already copied, launch these commands in directory which you copied project. (If you are using Windows, launch commands removing `./` )
```bash
./gradlew applyPatches
```

### Use Prismarine API
Prismarine doesn't support Maven yet.

Launch this command in your directory which copied project, Prismarine API will be installed Local Maven repository. (If you are using Windows, launch commands removing `./`)
```bash
./gradlew publishToMavenLocal
```
And add these information into your Dependency in API.

#### Gradle
```gradle
repositories {
  mavenLocal()
}
```

#### Maven
```xml
<repositories>
    <repository>
        <id>local-maven-repo</id>
        <url>file:///${project.parent.basedir}/local-maven-repo</url>
    </repository>
</repositories>
```

### Create patches and contribute to Prismarine
See [CONTRIBUTING.md](CONTRIBUTING.md)

### Create your own bukkit based on Prismarine
See [Prismarine-Template](https://github.com/PrismarineTeam/Prismarine-Template)

### Building a jar file
if you want to build API and server, use `./gradlew build`. Compiled JAR file will be generated in `Prismarine-API/build/libs` and `Prismarine-Server/build/libs`.

If you want to make server file, use `./gradlew createReobfPaperclipJar`. If you want to make Mojmap Jar file, use `./gradlew createMojmapPaperclipJar`. file will be generated in `build/libs`.

## Licenses
[![License](https://img.shields.io/github/license/PurpurMC/Purpur)](LICENSE.md)

If It doesn't written in header of patch file, This project will be granted license following [MIT License](src/LICENSES/ENG/MIT.md).

We've used these Other project's license in this project.

### [Creative Commons Zero Version 1.0 Universal](src/LICENSES/ENG/CC0_v1.0.md)
- [ArtixAllMighty/FixMySpawnR](https://github.com/ArtixAllMighty/FixMySpawnR)

### [Do What The F\*ck You Want To Public License](src/LICENSES/ENG/WTFPL.md)
- [Aizistral-Studios/No-Chat-Reports](https://github.com/Aizistral-Studios/No-Chat-Reports)

### [GNU General Public License Version 3.0](src/LICENSES/ENG/GNU_GPL_v3.0.md)
- [Akarin-project/Akarin](https://github.com/Akarin-project/Akarin)
- [Bukkit](https://hub.spigotmc.org/stash/projects/SPIGOT/repos/bukkit/browse)
- [CraftBukkit](https://hub.spigotmc.org/stash/projects/SPIGOT/repos/craftbukkit/browse)
- [PaperMC/Paper](https://github.com/PaperMC/Paper)
- [PatinaMC/Patina](https://github.com/PatinaMC/Patina)
   - Not specifically Written
- [Spigot](https://hub.spigotmc.org/stash/projects/SPIGOT/repos/spigot/browse)
- [Titaniumtown/JettPack](https://gitlab.com/Titaniumtown/JettPack)
- [pufferfish-gg/Pufferfish](https://github.com/pufferfish-gg/Pufferfish)

### [GNU Lesser General Public License Version 3.0](src/LICENSES/ENG/GNU_LGPL_v3.0.md)
- [CaffeineMC/lithium-fabric](https://github.com/CaffeineMC/lithium-fabric)

### [The MIT License](src/LICENSES/ENG/MIT.md)
- [Cryptite/Slice](https://github.com/Cryptite/Slice)
- [PurpurMC/Purpur](https://github.com/PurpurMC/Purpur)
- [RelativityMC/Concurrent Chunk Management Engine (C2ME-fabric)](https://github.com/RelativityMC/C2ME-fabric)
- [RelativityMC/Very Many Players (VMP-fabric)](https://github.com/RelativityMC/VMP-fabric)
- [The-Fireplace-Minecraft-Mods/Erroring-Entity-Remover](https://github.com/The-Fireplace-Minecraft-Mods/Erroring-Entity-Remover)

All License included in this project can be checked in [here](src/LICENSES/ENG/README.md).
