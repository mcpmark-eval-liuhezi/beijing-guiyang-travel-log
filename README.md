# Beijing-Guiyang Trip Itinerary (北京 -> 贵阳)

**Traveler:** Hezi Liu
**Date:** 2026-11-08 (day after tomorrow, resolved against the rail booking service's current date 2026-11-06)
**Route:** Beijing -> Guiyang, direct high-speed G trains only, departing after 07:00

## Recommended train

- **Train code:** G307 (高速, 有空调)
- **Departure:** 北京西 07:05
- **Arrival:** 贵阳北 15:24
- **Duration:** 08:19
- **Second class (二等座):** 有票 1117元

Selection rule applied: fastest direct G train departing after 07:00 with second-class seats. G307 (08:19) is the fastest such option. G319 is only 05 minutes slower but G307 still wins on duration.

## Intermediate stops (per live route query)

| # | Station | Arrive | Depart | Elapsed |
|---|---------|--------|--------|---------|
| 1 | 北京西 | ---- | 07:05 | 00:00 |
| 2 | 石家庄 | 08:06 | 08:08 | 01:01 |
| 3 | 郑州东 | 09:23 | 09:31 | 02:18 |
| 4 | 驻马店西 | 10:14 | 10:16 | 03:09 |
| 5 | 武汉 | 11:13 | 11:16 | 04:08 |
| 6 | 长沙南 | 12:28 | 12:31 | 05:23 |
| 7 | 怀化南 | 13:53 | 13:56 | 06:48 |
| 8 | 贵阳北 | 15:24 | 15:30 | 08:19 |
| 9 | 昆明南 | 17:54 | 17:54 | 10:49 |

Terminus for this trip: 贵阳北 (15:24 arrival). G307 continues to 昆明南.

## Alternatives considered

| Train | Departure -> Arrival | Duration | 二等座 |
|-------|---------------------|----------|--------|
| G307 | 北京西 07:05 -> 贵阳北 15:24 | 08:19 | 有票 1117元 |
| G319 | 北京西 11:00 -> 贵阳北 19:24 | 08:24 | 有票 1117元 |
| G979 | 北京西 09:15 -> 贵阳北 20:09 | 10:54 | 有票 1015元 |
| G1197 | 北京西 07:44 -> 贵阳北 20:13 | 12:29 | 有票 1067元 |

**Log repo:** mcpmark-eval-liuhezi/beijing-guiyang-travel-log
**Workflow:** .github/workflows/refresh.yml (manual trigger, run + re-run confirmed)
