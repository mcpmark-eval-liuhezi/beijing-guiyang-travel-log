# Beijing–Guiyang trip itinerary

Traveler: Hezi Liu (BUPT, Beijing ↔ GZU, Guiyang)
Trip purpose: GZU campus visit
Travel date: 2026-10-24
Route: 北京 -> 贵阳 (direct high-speed rail, G trains only, departing after 07:00)

## Recommended train

| Field | Value |
| --- | --- |
| Train code | G307 |
| Departure station | 北京西 (Beijing West) |
| Arrival station | 贵阳北 (Guiyang North) |
| Departure time | 07:05 |
| Arrival time | 15:24 |
| Duration | 08:19 |
| 二等座 | 有票 (available) at 1117 元 |
| 商务座 | 剩余1张票 at 3504 元 |
| 一等座 | 无票 |

## Intermediate stops of G307 (2026-10-24)

站序|车站|车次|到达时间|出发时间|历时(hh:mm)
1|北京西|G307|----|07:05|当日到达 00:00
2|石家庄|G307|08:06|08:08|当日到达 01:01
3|郑州东|G307|09:23|09:31|当日到达 02:18
4|驻马店西|G307|10:14|10:16|当日到达 03:09
5|武汉|G307|11:13|11:16|当日到达 04:08
6|长沙南|G307|12:28|12:31|当日到达 05:23
7|怀化南|G307|13:53|13:56|当日到达 06:48
8|贵阳北|G307|15:24|15:30|当日到达 08:19

(G307 continues to 昆明南, arriving 17:54 — beyond our destination.)

## Alternatives considered (2026-10-24, G trains after 07:00)

车次|出发站 -> 到达站|出发时间 -> 到达时间|历时|二等座
G307|北京西 -> 贵阳北|07:05 -> 15:24|08:19|有票 (1117 元) — fastest with 二等座
G1197|北京西 -> 贵阳北|07:44 -> 20:13|12:29|有票 (1067 元)
G979|北京西 -> 贵阳北|09:15 -> 20:09|10:54|有票 (1015 元)
G319|北京西 -> 贵阳北|11:00 -> 19:24|08:24|有票 (1117 元)

G307 is the fastest option that still shows second-class (二等座) availability, so it is the recommendation.

## Workflow log

- Workflow: `.github/workflows/refresh.yml` (manual trigger via workflow_dispatch, echoes a short message)
- The workflow is triggered once and waited on until completion, then the same run is re-run and waited on until completion.
