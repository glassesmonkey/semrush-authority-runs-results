# SERP 复核推荐词簇

二筛候选来源数：9
推荐词簇数：3
推荐关键词条目数：9

| 优先级 | 词簇数 | 关键词条目数 |
| --- | ---: | ---: |
| P0 | 0 | 0 |
| P1 | 1 | 6 |
| P2 | 2 | 3 |

优先级说明：
- P0：优先复核；供给可控、维护有界、差异化清楚，且不是由排列组合搜索量硬抬上来。
- P1：随后复核；机会成立，但数据供给、自然赢家或执行成本还需要确认。
- P2：长尾、cluster seed 或需数据源确认；不是自动拒绝。

## P1 - 球队对阵球员数据查询

- Canonical key: lookup/entity_pair/event_player_stats/sortable_data_page
- Badges: Supply=periodic_public_data; Freshness=event_bound; Control=medium; Winner=specialized_data_provider; Permutation=high
- 页面形态：按两队对阵生成的球员数据表，支持打者/投手拆分、排序、筛选和赛后关键指标摘要。
- 变现方式：广告、体育数据订阅导流、相关票务或装备联盟
- 为什么值得复核：Priority derived from semantic evidence; cap applied: natural winner is strong, but independent differentiation is credible.
- 关键词条目数：6；总搜索量：357300；最高 CPC：0

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| dodgers vs milwaukee brewers match player stats | 110000 | 39 | 0 | cap_P1 | 对阵球员统计查询页，提供双方阵容、打击/投球数据、关键球员表现和可排序指标表。 |
| milwaukee brewers vs dodgers match player stats | 110000 | 34 | 0 | cap_P1 | 对阵球员统计数据页，整合双方球员表现、球队分组、排序筛选和关键数据摘要。 |
| new york yankees vs toronto blue jays match player stats | 74000 | 37 | 0 | cap_P1 | 双方球员比赛数据表，支持按打击、投球、防守或关键指标筛选，并提供最近交手入口。 |
| kansas city royals vs detroit tigers match player stats | 33100 | 39 | 0 | cap_P1 | 两队比赛球员数据页，按球员、球队、位置和指标排序，附赛后摘要和历史对阵入口。 |
| colorado rockies vs red sox match player stats | 18100 | 32 | 0 | cap_P1 | 按两队对阵生成的球员数据表，支持打者/投手拆分、排序、筛选和赛后关键指标摘要。 |
| tampa bay rays vs st. louis cardinals match player stats | 12100 | 28 | 0 | cap_P1 | 比赛球员统计页，按球队和球员展示赛后数据、排序指标、关键表现和历史对阵链接。 |

## P2 - MLB 季后赛概率跟踪器

- Canonical key: tracker/many_permutations/playoff_odds/probability_table/team_or_scenario_optional
- Badges: Supply=live_external_data; Freshness=periodic; Control=weak; Winner=specialized_data_provider; Permutation=medium
- 页面形态：MLB 季后赛概率跟踪器，展示各队晋级概率、分区排名变化、情景模拟和模型假设说明。
- 变现方式：广告、体育数据订阅、联盟导流
- 为什么值得复核：Priority derived from semantic evidence; cap applied: dynamic or official data with weak/unknown supply control.
- 关键词条目数：1；总搜索量：18100；最高 CPC：6.85

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| mlb playoff odds | 18100 | 34 | 6.85 | cap_P2 | MLB 季后赛概率跟踪器，展示各队晋级概率、分区排名变化、情景模拟和模型假设说明。 |

## P2 - 球队对阵比赛时间线

- Canonical key: tracker/entity_pair/game_timeline/play_by_play_timeline
- Badges: Supply=live_external_data; Freshness=event_bound; Control=weak; Winner=specialized_data_provider; Permutation=high
- 页面形态：比赛时间线页，按局数和关键事件展示得分、换投、关键击球和胜率变化，可回看赛后时间轴。
- 变现方式：广告、数据订阅导流、体育相关联盟
- 为什么值得复核：Priority derived from semantic evidence; cap applied: dynamic or official data with weak/unknown supply control; high permutation inflation with weak/unknown canonical supply.
- 关键词条目数：2；总搜索量：41900；最高 CPC：0

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| detroit tigers vs seattle mariners timeline | 27100 | 34 | 0 | cap_P2 | 比赛时间线页，按局数和关键事件展示得分、换投、关键击球和胜率变化，可回看赛后时间轴。 |
| seattle mariners vs detroit tigers timeline | 14800 | 36 | 0 | cap_P2 | 对阵比赛时间线，按时间或局数展示关键事件、比分变化、球员动作和赛后回放视图。 |
