# 포팅된 패치
### **한국어** - [English](ENG.md)

## [Paper](https://github.com/PaperMC/Paper)
- [Machine Maker](https://github.com/Machine-Maker) - Use DataConverter for itemstack/entity deserialization (PaperMC/Paper#7068)
- [Machine Maker](https://github.com/Machine-Maker) - Use team display name for quit message (PaperMC/Paper#7127)
- [dannyball710](https://github.com/dannyball710) - Ignore BaseSpawner impossible spawn tick (PaperMC/Paper#7469)
- [Machine Maker](https://github.com/Machine-Maker) - Fix async entity add due to fungus trees (PaperMC/Paper#7626)
- [booky10](https://github.com/booky10) - Prevent healing by negative amounts (PaperMC/Paper#7703)
   - Edited by [AlphaKR93](https://github.com/AlphaKR93)
- [Spottedleaf](https://github.com/Spottedleaf) - \[DEV-BRANCH\] Rewrite chunk system (PaperMC/Paper#8177)
   - [Prismarine 공식 디스코드](https://discord.gg/kkqMSEVVxN)에서만 다운로드 할 수 있습니다.

## [Purpur](https://github.com/PurpurMC/Purpur)
- [BillyGalbreath](https://github.com/BillyGalbreath), [granny](https://github.com/granny), **[theomega24](https://github.com/theomega24)** - Make the GUI great again! (PurpurMC/Purpur#676)
- [DaRacci](https://github.com/DaRacci) - Add Fire ImmunityAPI (PurpurMC/Purpur#891)
- [YouHaveTrouble](https://github.com/YouHaveTrouble) - Add ability to place and remove block debug markers for players (PurpurMC/Purpur#1072)
- [SageSphinx63920](https://github.com/SageSphinx63920) - Add Bee API (PurpurMC/Purpur#1082)

## [Akarin](https://github.com/Akarin-project/Akarin)
- 서버 패치
   - [0007 - Avoid double I/O operation on load player file](https://github.com/Akarin-project/Akarin/blob/ver/1.16.5/patches/server/0007-Avoid-double-I-O-operation-on-load-player-file.patch)
   - [0008 - Don't trigger Lootable Refresh for non player interaction](https://github.com/Akarin-project/Akarin/blob/ver/1.16.5/patches/server/0008-Don-t-trigger-Lootable-Refresh-for-non-player-intera.patch)
   - [0011 - Swaps the predicate order of collision](https://github.com/Akarin-project/Akarin/blob/ver/1.16.5/patches/server/0011-Swaps-the-predicate-order-of-collision.patch)

## [JettPack](https://gitlab.com/Titaniumtown/JettPack)
- 서버 패치
   - [0003 - Use LinkedBlockingDeque in IAsyncTaskHandler](https://gitlab.com/Titaniumtown/JettPack/-/blob/main/patches/server/0003-Use-LinkedBlockingDeque-in-IAsyncTaskHandler.patch)
   - [0005 - lithium: HashedList](https://gitlab.com/Titaniumtown/JettPack/-/blob/main/patches/server/0005-lithium-HashedList.patch)
   - [0008 - Better handling of async tasks](https://gitlab.com/Titaniumtown/JettPack/-/blob/main/patches/server/0008-Better-handling-of-async-tasks.patch)
   - [0009 - Use MCUtil.asyncExecutor for MAIN_WORKER_EXECUTOR in Util](https://gitlab.com/Titaniumtown/JettPack/-/blob/main/patches/server/0009-Use-MCUtil.asyncExecutor-for-MAIN_WORKER_EXECUTOR-in.patch)
   - [0011 - (Yatopia) New nbt cache](https://gitlab.com/Titaniumtown/JettPack/-/blob/main/patches/server/0011-Yatopia-New-nbt-cache.patch)
   - [0012 - configurable logging of player login location](https://gitlab.com/Titaniumtown/JettPack/-/blob/main/patches/server/0012-configurable-logging-of-player-login-location.patch)
   - [0013 - configurable fishing rod length](https://gitlab.com/Titaniumtown/JettPack/-/blob/main/patches/server/0013-configurable-fishing-rod-length.patch)
   - [0014 - remove 'sync-chunk-writes' in server.properties](https://gitlab.com/Titaniumtown/JettPack/-/blob/main/patches/server/0014-remove-sync-chunk-writes-in-server.properties.patch)
   - [0020 - lithium: replace AI goal set with optimized collection](https://gitlab.com/Titaniumtown/JettPack/-/blob/main/patches/server/0020-lithium-replace-AI-goal-set-with-optimized-collectio.patch)
   - [0021 - lithium: math.fast_util](https://gitlab.com/Titaniumtown/JettPack/-/blob/main/patches/server/0021-lithium-math.fast_util.patch)
   - [0022 - lithium: entity.fast_retrieval](https://gitlab.com/Titaniumtown/JettPack/-/blob/main/patches/server/0022-lithium-entity.fast_retrieval.patch)
   - [0023 - lithium: cached_hashcode](https://gitlab.com/Titaniumtown/JettPack/-/blob/main/patches/server/0023-lithium-cached_hashcode.patch)
   - [0027 - Remove unnecessary getLogger()](https://gitlab.com/Titaniumtown/JettPack/-/blob/main/patches/server/0027-Remove-unnecessary-getLogger.patch)
   - [0028 - lithium: shapes.precompute_shape_arrays](https://gitlab.com/Titaniumtown/JettPack/-/blob/main/patches/server/0028-lithium-shapes.precompute_shape_arrays.patch)
   - [0029 - cache bukkitVersion](https://gitlab.com/Titaniumtown/JettPack/-/blob/main/patches/server/0029-cache-bukkitVersion.patch)
   - [0031 - (VMP) ingredient matching cache](https://gitlab.com/Titaniumtown/JettPack/-/blob/main/patches/server/0031-VMP-ingredient-matching-cache.patch)
- API 패치
   - [0001 - skip event if no listeners](https://gitlab.com/Titaniumtown/JettPack/-/blob/main/patches/api/0001-skip-event-if-no-listeners.patch)

## [Patina](https://github.com/PatinaMC/Patina)
- 서버 패치
   - [0009 - remove TickTask](https://github.com/PatinaMC/Patina/blob/ver/1.19.2/patches/server/0008-remove-TickTask.patch)
   - [0011 - don't create new random instance](https://github.com/PatinaMC/Patina/blob/ver/1.19.2/patches/server/0010-don-t-create-new-random-instance.patch)
   - [0012 - completely remove bootstrapExecutor](https://github.com/PatinaMC/Patina/blob/ver/1.19.2/patches/server/0011-completely-remove-bootstrapExecutor.patch)
- API 패치
   - [0005 - Suspected plugins report](https://github.com/PatinaMC/Patina/blob/ver/1.19.2/patches/api/0005-Suspected-plugins-report.patch)

## [Slice](https://github.com/Cryptite/Slice)
- 서버 패치
   - [0004 - Don't send equipment updates if only durability changed](https://github.com/Cryptite/Slice/blob/master/patches/server/0004-Don-t-send-equipment-updates-if-only-durability-chan.patch)
   - [0006 - Don't send fire packets if player has Fire Resistance](https://github.com/Cryptite/Slice/blob/master/patches/server/0006-Don-t-send-fire-packets-if-player-has-Fire-Resistanc.patch)
   - [0012 - Packet obfuscation and reduction](https://github.com/Cryptite/Slice/blob/master/patches/server/0012-Packet-obfuscation-and-reduction.patch)

<!-- 
## [Mirai](https://github.com/etil2jz/Mirai)
## [EmpireCraft](https://github.com/starlis/EmpireCraft)
## [Origami](https://github.com/Minebench/Origami)
 -->