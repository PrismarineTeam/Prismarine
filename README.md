<div align="center">

Prismarine
=
[![License](https://img.shields.io/github/license/PrismarineTeam/Prismarine)](https://github.com/PrismarineTeam/Prismarine/blob/ver/1.19/LICENSE.md)
[![Build Prismarine](https://img.shields.io/github/workflow/status/PrismarineTeam/Prismarine/Build%20Prismarine)](https://github.com/PrismarineTeam/Prismarine/actions/workflows/build.yml)
[![Open Issues](https://img.shields.io/github/issues-raw/PrismarineTeam/Prismarine?label=issues)](https://github.com/PrismarineTeam/Prismarine/issues)
[![Open PRs](https://img.shields.io/github/issues-pr-raw/PrismarineTeam/Prismarine?label=pull%20requests)](https://github.com/PrismarineTeam/Prismarine/pulls)

[![Forks](https://img.shields.io/github/forks/PrismarineTeam/Prismarine)](https://github.com/PrismarineTeam/Prismarine/network/members)
[![Stars](https://img.shields.io/github/stars/PrismarineTeam/Prismarine)](https://github.com/PrismarineTeam/Prismarine/stargazers)
[![Watchers](https://img.shields.io/github/watchers/PrismarineTeam/Prismarine)](https://github.com/PrismarineTeam/Prismarine/watchers)
[![Discord](https://img.shields.io/discord/781822976773455882?color=%235865F2&label=Discord&logo=discord)](https://discord.gg/kkqMSEVVxN)

[Discord](https://discord.gg/kkqMSEVVxN) | [한국어](src/README/KOR.md) - **English**

A Server Platform for Minecraft: Java Edition with many improvements based on [Paper](https://github.com/PaperMC/Paper)

*You can support this project through the right (or bottom) Sponsor*

</div>

## Features
- Based on [Bukkit](https://hub.spigotmc.org/stash/projects/SPIGOT/repos/bukkit/browse), [CraftBukkit](https://hub.spigotmc.org/stash/projects/SPIGOT/repos/craftbukkit/browse), [Spigot](https://hub.spigotmc.org/stash/projects/SPIGOT/repos/spigot/browse) and [Paper](https://github.com/PaperMC/Paper), most plugins are fully supported and stable.
- Supports faster speeds and wider APIs, including all patches from [Pufferfish](https://github.com/pufferfish-gg/Pufferfish) and [Purpur](https://github.com/PurpurMC/Purpur).
- Multiple improvements and bug resolution were included by porting multiple mods.
- [Patina](https://github.com/PatinaMC/Patina), [JettPack](https://gitlab.com/Titaniumtown/JettPack), [EmpireCraft](https://github.com/starlis/EmpireCraft), [Akarin](https://github.com/Akarin-project/Akarin), [Slice](https://github.com/Cryptite/Slice)
- It provides better performance than other bukkit by excluding all the unstable, old, or unnecessary parts of a bukkit optimized for a particular user.
- Improve quality of server by porting patches disappeared or remained as a PR.
   - Ported patches can be found at [HERE](src/PORTED_PATCHES/ENG.md) 
- Provides the fastest upstream by using GitHub Action which do upstream automatically.

## Communicate
[![Discord](https://img.shields.io/discord/781822976773455882?color=%235865F2&label=Discord&logo=discord)](https://discord.gg/kkqMSEVVxN)

Join [Discord](https://discord.gg/kkqMSEVVxN) and let us know error and help us find how to solve it!

## [#saveminecraft](https://saveminecraft.org/)
[#saveminecraft](https://saveminecraft.org/)는 Minecraft: Java Edition의 1.19.1(1.**19.84**라고도 불림)에 Mojang Studios와 Microsoft에 의해 추가된 채팅 신고 기능에 반대하는 운동입니다. saveminecraft 운동의 목표는 Minecraft의 멀티 플레이를 위험에 빠뜨리지 않고 서버의 관리자에게 권한을 부여하는 새로운 채팅 신고 기능을 추가하거나, 채팅 신고 기능을 완전히 제거하는 것입니다. saveminecraft 운동은 이 변화를 평화적으로 항의하고 인식을 확산하고자 합니다. **자세한 내용은 [여기를](../SAVEMINECRAFT/ENG.md) 확인해주시기 바랍니다.**

Prismarine은 이 운동을 지지하고, 채팅 신고 기능을 완전히 제거하여 Minecraft의 멀티 플레이를 위험에 빠뜨리는것이 아닌, 서버 관리자에게 권한을 부여하는 새로운 채팅 신고 기능의 추가를 목표로 하고 있습니다.

Prismarine은 서버 관리자가 채팅 신고 기능을 활성화 하거나, 비활성화 할 수 있도록 개발되었습니다.
기본적으로 활성화 되어 있지만, 비활성화 하고 싶다면 `prismarine.yml` 에서 비활성화 할 수 있습니다. (기능 제공: [No Chat Reports](https://modrinth.com/mod/no-chat-reports))

## Downloads
[![Build Prismarine](https://img.shields.io/github/workflow/status/PrismarineTeam/Prismarine/Build%20Prismarine)](https://github.com/PrismarineTeam/Prismarine/releases/tag/latest)

In normal case, you can download latest JAR file by clicking [THIS](https://github.com/PrismarineTeam/Prismarine/releases/download/latest/Prismarine-paperclip-1.19-R0.1-SNAPSHOT-reobf.jar) 
Mojmap or Bundler Jar can be downloaded [right side(or below)'s Releases tab](https://github.com/PrismarineTeam/Prismarine/releases/tag/latest).

## Configuration & Optimize
See [Wiki](https://github.com/PrismarineTeam/Prismarine/wiki)

## For Developers
### Requirements
You needs latest Git, JDK upper than 17.

Git should set `user.emal` and `user.name`

If you want to set, use these commands in your terminal.
```bash
git config --global user.email "<your GitHub E-mail>"
git config --global user.name "<your GitHub ID>"
```

### Initial Setup
First, launch these commands in directory which you want to copy project.
```bash
git clone -b dev/1.19 https://github.com/PrismarineTeam/Prismarine
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

### Create your own bucket based on Prismarine
See [Prismarine-Template](https://github.com/PrismarineTeam/Prismarine-Template)

### Building a jar file
if you want to build API and server, use `./gradlew build`. Compiled JAR file will be generated in `Prismarine-API/build/libs` and `Prismarine-Server/build/libs`.

If you want to make server file, use `./gradlew createReobfPaperclipJar`. If you want to make Mojmap Jar file, use `./gradlew createMojmapPaperclipJar`. file will be generated in `build/libs`.

## Licenses
[![License](https://img.shields.io/github/license/PrismarineTeam/Prismarine)](https://github.com/PrismarineTeam/Prismarine/blob/ver/1.19/LICENSE.md)

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

All License included in this project can be checked in [HERE](src/LICENSES/ENG/README.md).
