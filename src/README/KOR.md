<div align="center">

# Prismarine
[![License](https://img.shields.io/github/license/PurpurMC/Purpur?label=라이선스)](LICENSE.md)
[![Build Prismarine](https://img.shields.io/github/workflow/status/PrismarineTeam/Prismarine/Build%20Prismarine?label=빌드)](https://github.com/PrismarineTeam/Prismarine/actions/workflows/build.yml)
[![Upstream Prismarine](https://img.shields.io/github/workflow/status/PrismarineTeam/PrismarineManager/Scheduled%20Upstream%20(1.19.2)?label=업스트림)](https://github.com/PrismarineTeam/PrismarineManager/actions/workflows/prismarine.yml)

**:kr: 한국어** - [:us: English](../../README.md)

[Paper](https://github.com/PaperMC/Paper) 기반의 여러 개선이 추가된 Minecraft: Java Edition 용 서버 플랫폼

*우측(또는 하단) Sponsor를 통해 이 프로젝트를 지원하실 수 있습니다!*

</div>

## Prismarine 만의 장점
- [Bukkit](https://hub.spigotmc.org/stash/projects/SPIGOT/repos/bukkit/browse), [CraftBukkit](https://hub.spigotmc.org/stash/projects/SPIGOT/repos/craftbukkit/browse), [Spigot](https://hub.spigotmc.org/stash/projects/SPIGOT/repos/spigot/browse), [Paper](https://github.com/PaperMC/Paper) 기반으로 안정적이며, 대부분의 플러그인을 완벽히 지원합니다.
- [Pufferfish](https://github.com/pufferfish-gg/Pufferfish), [Purpur](https://github.com/PurpurMC/Purpur)의 모든 패치를 포함하여 더 빠른 속도와 더 넓은 API를 지원합니다.
- 여러 모드를 포팅하여 버그를 해결하고 여러 개선이 제공됩니다.
- [Patina](https://github.com/PatinaMC/Patina), [JettPack](https://gitlab.com/Titaniumtown/JettPack), [EmpireCraft](https://github.com/starlis/EmpireCraft), [Akarin](https://github.com/Akarin-project/Akarin), [Slice](https://github.com/Cryptite/Slice), [Petal](https://github.com/bloom-host/Petal) 등 불안정하거나, 오래되었거나, 특정 사용자를 위해 최적화된 버킷에서 불안정하고 불필요한 부분은 모두 제외하고 필요한 부분만 포팅하여 다른 버킷 보다 더 좋은 성능을 제공합니다.
- 사라지거나 아직 PR로 남은 패치를 포팅하여 서버 사용을 개선합니다.
   - 포팅된 패치는 [여기서](../PORTED_PATCHES/KOR.md) 확인할 수 있습니다.
- GitHub Action 을 사용하여 자동적으로 업스트림을 진행해 버킷중에서 가장 빠른 업스트림을 제공합니다.
- 채팅 신고 기능을 비활성화 할 수 있습니다.

## 소통하기 [<img src="https://github.com/intergrav/devins-badges/blob/v2/assets/minimal/social/twitter-singular_64h.png?raw=true" width="20px"></img>](https://twitter.com/TeamPrismarine)
[<img src="https://discord.com/api/guilds/781822976773455882/widget.png?style=banner3"></img>](https://discord.gg/kkqMSEVVxN)
[<img src="https://discord.com/api/guilds/1003295972203429949/widget.png?style=banner3"></img>](https://discord.gg/CQGVqeXQQC)

[Discord](https://discord.gg/kkqMSEVVxN)에 접속해서 오류를 공유하고 해결 방법을 찾아보세요!

### 유용한 서버
- [Minecraft Development Dictionary (MDD)](https://discord.gg/AZwXTA9Pgx)
   - Minecraft에 관련된 다양한 뉴스, 소식과 서버 개발에 대한 정보를 얻고 질문&답변 할 수 있습니다.

- [Minecraft Customization Community (MCC)](https://discord.gg/nnkecH6n24)
   - Minecraft의 모드, 리소스팩, 셰이더에 대한 정보를 얻고 질문&답변 할 수 있습니다.

## [#saveminecraft](https://saveminecraft.org/)
[#saveminecraft](https://saveminecraft.org/)는 Minecraft: Java Edition의 1.19.1(1.**19.84**라고도 불림)에 Mojang Studios와 Microsoft에 의해 추가된 채팅 신고 기능에 반대하는 운동입니다. saveminecraft 운동의 목표는 Minecraft의 멀티 플레이를 위험에 빠뜨리지 않고 서버의 관리자에게 권한을 부여하는 새로운 채팅 신고 기능을 추가하거나, 채팅 신고 기능을 완전히 제거하는 것입니다. saveminecraft 운동은 이 변화를 평화적으로 항의하고 인식을 확산하고자 합니다. **자세한 내용은 [여기를](../SAVEMINECRAFT/KOR.md) 확인해주시기 바랍니다.**

Prismarine은 이 운동을 지지하고, 채팅 신고 기능을 완전히 제거하여 Minecraft의 멀티 플레이를 위험에 빠뜨리는것이 아닌, 서버 관리자에게 권한을 부여하는 새로운 채팅 신고 기능의 추가를 목표로 하고 있습니다.

Prismarine은 서버 관리자가 채팅 신고 기능을 활성화 하거나, 비활성화 할 수 있도록 개발되었습니다.
기본적으로 활성화 되어 있지만, 비활성화 하고 싶다면 `prismarine.yml` 에서 비활성화 할 수 있습니다. (기능 제공: [No Chat Reports](https://modrinth.com/mod/no-chat-reports))

### #saveminecraft 운동에 참여하기
[Change.org 청원](https://chng.it/4MQX8YybMf)에 참여해주세요. 가입은 필요하지 않습니다.

[#saveminecraft 운동 디스코드](https://discord.gg/saveminecraft)에 접속해주세요.

[여기에](https://saveminecraft.org/opinions) 자신의 의견을 남겨주세요. Google 계정 또는 GitHub 계정이 필요합니다.

그리고, 이 운동을 퍼뜨려주세요. 채팅 신고 기능이 사라질 수 있도록 도와주세요.

## 다운로드
[![Build Prismarine](https://img.shields.io/github/workflow/status/PrismarineTeam/Prismarine/Build%20Prismarine)](https://github.com/PrismarineTeam/Prismarine/releases/tag/latest)

일반적인 경우 [여기를 클릭하여](https://github.com/PrismarineTeam/Prismarine/releases/download/latest/Prismarine-paperclip-1.19.2-R0.1-SNAPSHOT-reobf.jar) 최신 버킷 Jar 파일을 다운로드 받을 수 있습니다.

Mojmap 또는 Bundler Jar는 [우측(또는 아래) Releases 탭](https://github.com/PrismarineTeam/Prismarine/releases/tag/latest)의 가장 하단에서 다운로드 할 수 있습니다.

## 구성 및 최적화
[여기를](https://github.com/PrismarineTeam/Prismarine/wiki) 확인해주세요.

## 개발자를 위한 섹션
### Requirements
터미널에서 사용 가능한 최신 버전의 Git, 17 이상의 JDK가 필요합니다.

Git은 `user.email` 과 `user.name` 구성이 설정되어 있어야 합니다.

설정하려면 다음의 명렁을 터미널에서 실행하세요.
```bash
git config --global user.email "<내 GitHub 이메일 주소>"
git config --global user.name "<내 GitHub 아이디>"
```

### Initial Setup
먼저, 프로젝트를 복사할 디렉토리에서 다음 명령어를 실행하세요.
```bash
git clone -b ver/1.19.2 https://github.com/PrismarineTeam/Prismarine
```
프로젝트가 복사되었거나 이미 복사했다면, 프로젝트를 복사한 경로에서 다음 명령어를 실행하세요. (Windows 사용자의 경우 앞 `./` 를 지우고 명령을 실행하세요)
```bash
./gradlew applyPatches
```

### Use Prismarine API
Prismarine은 아직 API를 제대로 지원하지 않습니다.

프로젝트가 복사된 경로에서 다음 명령어를 실행하면 Prismarine API를 로컬 Maven 레포지토리에 설치합니다. (Windows 사용자의 경우 앞 `./` 를 지우고 명령을 실행하세요)
```bash
./gradlew publishToMavenLocal
```
그리고 API의 Dependency에 다음 정보를 추가하세요.

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
[CONTRIBUTING.md](../CONTRIBUTING/KOR.md) 를 확인해주세요.

### Create your own bucket based on Prismarine
[Prismarine-Template](https://github.com/PrismarineTeam/Prismarine-Template/blob/ver/1.19.2/src/README/KOR.md) 을 확인해주세요.

### Building a jar file
API와 서버를 빌드하려면 `./gradlew build` 를 사용하세요. 컴파일된 JAR 파일은 `Prismarine-API/build/libs` 와 `Prismarine-Server/build/libs` 에 생성될 것입니다.

실행 가능한 서버 파일을 만드려면, `./gradlew createReobfPaperclipJar` 를 사용하세요. Mojmap Jar 파일을 만드려면 `./gradlew createMojmapPaperclipJar` 를 사용하세요. 파일은 `build/libs` 에 생성될 것입니다.

## 라이선스
[![License](https://img.shields.io/github/license/PurpurMC/Purpur)](LICENSE.md)

패치 파일의 헤더에 따로 명시되지 않은 한, 본 프로젝트는 [MIT License](../LICENSES/KOR/MIT.md)에 따라 라이선스가 부여됩니다.

본 프로젝트에 포함된 다른 프로젝트의 라이선스는 다음과 같습니다.

### [크리에이티브 제로 커먼즈 버전 1.0 보편적](../LICENSES/KOR/CC0_v1.0.md)
- [ArtixAllMighty/FixMySpawnR](https://github.com/ArtixAllMighty/FixMySpawnR)

### [Do What The F\*ck You Want To Public 허가서](../LICENSES/KOR/WTFPL.md)
- [Aizistral-Studios/No-Chat-Reports](https://github.com/Aizistral-Studios/No-Chat-Reports)

### [GNU 일반 공중 사용 허가서 버전 3.0](../LICENSES/KOR/GNU_GPL_v3.0.md)
- [Akarin-project/Akarin](https://github.com/Akarin-project/Akarin)
- [Bukkit](https://hub.spigotmc.org/stash/projects/SPIGOT/repos/bukkit/browse)
- [CraftBukkit](https://hub.spigotmc.org/stash/projects/SPIGOT/repos/craftbukkit/browse)
- [PaperMC/Paper](https://github.com/PaperMC/Paper)
- [PatinaMC/Patina](https://github.com/PatinaMC/Patina)
   - 명시되어 있지 않음
- [Spigot](https://hub.spigotmc.org/stash/projects/SPIGOT/repos/spigot/browse)
- [Titaniumtown/JettPack](https://gitlab.com/Titaniumtown/JettPack)
- [pufferfish-gg/Pufferfish](https://github.com/pufferfish-gg/Pufferfish)

### [GNU 약소 일반 공중 사용 허가서 버전 3.0](../LICENSES/KOR/GNU_LGPL_v3.0.md)
- [CaffeineMC/lithium-fabric](https://github.com/CaffeineMC/lithium-fabric)

### [MIT 허가서](../LICENSES/KOR/MIT.md)
- [Cryptite/Slice](https://github.com/Cryptite/Slice)
- [EmpireCraft/EmpireCraft](https://github.com/starlis/EmpireCraft)
- [PurpurMC/Purpur](https://github.com/PurpurMC/Purpur)
- [RelativityMC/Concurrent Chunk Management Engine (C2ME-fabric)](https://github.com/RelativityMC/C2ME-fabric)
- [RelativityMC/Very Many Players (VMP-fabric)](https://github.com/RelativityMC/VMP-fabric)
- [The-Fireplace-Minecraft-Mods/Erroring-Entity-Remover](https://github.com/The-Fireplace-Minecraft-Mods/Erroring-Entity-Remover)

본 프로젝트에 포함된 모든 프로젝트의 라이선스는 [여기서](../LICENSES/KOR/README.md) 확인할 수 있습니다.
