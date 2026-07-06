# SERP 复核推荐词簇

二筛候选来源数：583
推荐词簇数：20
推荐关键词条目数：583

| 优先级 | 词簇数 | 关键词条目数 |
| --- | ---: | ---: |
| P0 | 0 | 0 |
| P1 | 7 | 75 |
| P2 | 13 | 508 |

优先级说明：
- P0：优先复核；供给可控、维护有界、差异化清楚，且不是由排列组合搜索量硬抬上来。
- P1：随后复核；机会成立，但数据供给、自然赢家或执行成本还需要确认。
- P2：长尾、cluster seed 或需数据源确认；不是自动拒绝。

## P1 - NBA 球队深度名单查询

- Canonical key: lookup/single_entity/team_depth_chart/roster_depth_table/team
- Badges: Supply=periodic_public_data; Freshness=periodic; Control=medium; Winner=specialized_data_provider; Permutation=medium
- 页面形态：球队深度名单表，按位置、首发/替补、伤病状态和近期轮换排序。
- 变现方式：广告、幻想体育 affiliate、订阅型高级阵容提醒。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: natural winner is strong, but independent differentiation is credible.
- 关键词条目数：3；总搜索量：39000；最高 CPC：4.44

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| pelicans depth chart | 14800 | 40 | 4.44 | cap_P1 | 球队深度名单表，按位置、首发/替补、伤病状态和近期轮换排序。 |
| timberwolves depth chart | 12100 | 25 | 3.82 | cap_P1 | 球队深度名单表，按位置、首发/替补、伤病状态和近期轮换排序。 |
| raptors depth chart | 12100 | 39 | 3.75 | cap_P1 | 球队深度名单表，按位置、首发/替补、伤病状态和近期轮换排序。 |

## P1 - 球队深度阵容表

- Canonical key: lookup/single_entity/team_depth_chart/position_depth_table/team
- Badges: Supply=periodic_public_data; Freshness=periodic; Control=weak; Winner=specialized_data_provider; Permutation=medium
- 页面形态：球队深度阵容表，按位置展示首发、替补、伤病状态和最近更新时间。
- 变现方式：广告、梦幻体育工具或体育数据订阅导流。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: maintenance burden is medium and supply control is not strong.
- 关键词条目数：4；总搜索量：63100；最高 CPC：4.04

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| hornets depth chart | 18100 | 39 | 4.04 | cap_P1 | 球队深度阵容表，按位置展示首发、替补、伤病状态和最近更新时间。 |
| magic depth chart | 12100 | 34 | 3.41 | cap_P1 | 球队深度阵容表，按位置展示首发、替补、伤病状态和最近更新时间。 |
| wizards depth chart | 14800 | 38 | 2.94 | cap_P1 | 球队深度表页，按位置展示首发、替补、伤停影响和最近更新时间。 |
| knicks depth chart | 18100 | 30 | 2.81 | cap_P1 | 球队深度阵容表，按位置展示首发、替补、伤病状态和最近更新时间。 |

## P1 - 球队阵容深度表查询

- Canonical key: lookup/single_entity/team_depth_chart/position_depth_table/team_name
- Badges: Supply=periodic_public_data; Freshness=periodic; Control=medium; Winner=specialized_data_provider; Permutation=medium
- 页面形态：球队 depth chart 数据页，按位置展示首发、替补、伤停状态和最近更新时间。
- 变现方式：广告、Fantasy/体育投注工具导流、球队页面内链。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: natural winner is strong, but independent differentiation is credible.
- 关键词条目数：2；总搜索量：32900；最高 CPC：3.43

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| bucks depth chart | 14800 | 30 | 3.43 | cap_P1 | 球队 depth chart 数据页，按位置展示首发、替补、伤停状态和最近更新时间。 |
| 76ers depth chart | 18100 | 37 | 3.28 | cap_P1 | 球队 depth chart 数据页，按位置展示首发、替补、伤停状态和最近更新时间。 |

## P1 - 球队对阵球员数据查询

- Canonical key: lookup/entity_pair/event_player_stats/sortable_data_page/team_a_vs_team_b
- Badges: Supply=periodic_public_data; Freshness=event_bound; Control=weak; Winner=specialized_data_provider; Permutation=high
- 页面形态：球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。
- 变现方式：广告、体育数据订阅导流、球队/球员页面内链。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: high permutation inflation with weak/unknown canonical supply.
- 关键词条目数：272；总搜索量：8021700；最高 CPC：3.34

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| golden state warriors vs la clippers match player stats | 135000 | 28 | 3.34 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| phoenix suns vs oklahoma city thunder match player stats | 201000 | 39 | 1.49 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| phoenix suns vs golden state warriors match player stats | 60500 | 40 | 1.25 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| charlotte hornets vs celtics match player stats | 60500 | 38 | 1.19 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| brooklyn nets vs atlanta hawks match player stats | 14800 | 37 | 1.12 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| timberwolves vs denver nuggets match player stats | 301000 | 39 | 1.1 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| 76ers vs boston celtics match player stats | 135000 | 38 | 1.03 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| lakers vs dallas mavericks match player stats | 135000 | 40 | 0.94 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| timberwolves vs atlanta hawks match player stats | 14800 | 34 | 0.42 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| houston rockets vs golden state warriors match player stats | 201000 | 38 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| la clippers vs golden state warriors match player stats | 135000 | 28 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| charlotte hornets vs orlando magic match player stats | 90500 | 35 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| lakers vs toronto raptors match player stats | 90500 | 39 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| celtics vs milwaukee bucks match player stats | 74000 | 39 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| charlotte hornets vs golden state warriors match player stats | 74000 | 32 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| la clippers vs utah jazz match player stats | 74000 | 38 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| lakers vs portland trail blazers match player stats | 74000 | 40 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| 76ers vs chicago bulls match player stats | 60500 | 36 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| 76ers vs washington wizards match player stats | 60500 | 35 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| celtics vs cleveland cavaliers match player stats | 60500 | 36 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| golden state warriors vs portland trail blazers match player stats | 60500 | 37 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| golden state warriors vs sacramento kings match player stats | 60500 | 32 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| lakers vs orlando magic match player stats | 60500 | 39 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| memphis grizzlies vs golden state warriors match player stats | 60500 | 35 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| memphis grizzlies vs lakers match player stats | 60500 | 40 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| san antonio spurs vs golden state warriors match player stats | 60500 | 29 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| san antonio spurs vs new orleans pelicans match player stats | 60500 | 34 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| 76ers vs milwaukee bucks match player stats | 49500 | 36 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| atlanta hawks vs detroit pistons match player stats | 49500 | 36 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| charlotte hornets vs milwaukee bucks match player stats | 49500 | 35 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| golden state warriors vs dallas mavericks match player stats | 49500 | 40 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| golden state warriors vs milwaukee bucks match player stats | 49500 | 37 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| golden state warriors vs orlando magic match player stats | 49500 | 27 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| houston rockets vs dallas mavericks match player stats | 49500 | 40 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| knicks vs orlando magic match player stats | 49500 | 30 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| la clippers vs phoenix suns match player stats | 49500 | 34 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| lakers vs charlotte hornets match player stats | 49500 | 40 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| portland trail blazers vs denver nuggets match player stats | 49500 | 37 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| sacramento kings vs denver nuggets match player stats | 49500 | 38 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| sacramento kings vs phoenix suns match player stats | 49500 | 36 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| 76ers vs charlotte hornets match player stats | 40500 | 40 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| 76ers vs detroit pistons match player stats | 40500 | 33 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| atlanta hawks vs orlando magic match player stats | 40500 | 25 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| brooklyn nets vs san antonio spurs match player stats | 40500 | 31 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| charlotte hornets vs knicks match player stats | 40500 | 39 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| charlotte hornets vs miami heat match player stats | 40500 | 39 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| golden state warriors vs pacers match player stats | 40500 | 37 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| golden state warriors vs utah jazz match player stats | 40500 | 27 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| knicks vs chicago bulls match player stats | 40500 | 37 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| sacramento kings vs golden state warriors match player stats | 40500 | 37 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| san antonio spurs vs detroit pistons match player stats | 40500 | 38 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| 76ers vs memphis grizzlies match player stats | 33100 | 36 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| 76ers vs san antonio spurs match player stats | 33100 | 35 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| atlanta hawks vs cleveland cavaliers match player stats | 33100 | 37 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| atlanta hawks vs washington wizards match player stats | 33100 | 36 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| celtics vs atlanta hawks match player stats | 33100 | 37 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| celtics vs oklahoma city thunder match player stats | 33100 | 38 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| charlotte hornets vs lakers match player stats | 33100 | 37 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| houston rockets vs sacramento kings match player stats | 33100 | 37 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| la clippers vs portland trail blazers match player stats | 33100 | 38 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| memphis grizzlies vs la clippers match player stats | 33100 | 40 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| phoenix suns vs denver nuggets match player stats | 33100 | 38 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| phoenix suns vs houston rockets match player stats | 33100 | 38 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| phoenix suns vs portland trail blazers match player stats | 33100 | 39 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| phoenix suns vs san antonio spurs match player stats | 33100 | 34 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| portland trail blazers vs utah jazz match player stats | 33100 | 36 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| sacramento kings vs milwaukee bucks match player stats | 33100 | 35 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| sacramento kings vs oklahoma city thunder match player stats | 33100 | 35 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| sacramento kings vs timberwolves match player stats | 33100 | 37 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| san antonio spurs vs memphis grizzlies match player stats | 33100 | 33 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| san antonio spurs vs timberwolves match player stats | 33100 | 39 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| 76ers vs atlanta hawks match player stats | 27100 | 38 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| 76ers vs lakers match player stats | 27100 | 40 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| 76ers vs orlando magic match player stats | 27100 | 39 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| atlanta hawks vs 76ers match player stats | 27100 | 39 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| atlanta hawks vs denver nuggets match player stats | 27100 | 33 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| atlanta hawks vs golden state warriors match player stats | 27100 | 30 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| atlanta hawks vs pacers match player stats | 27100 | 33 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| brooklyn nets vs knicks match player stats | 27100 | 26 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| charlotte hornets vs atlanta hawks match player stats | 27100 | 39 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| charlotte hornets vs pacers match player stats | 27100 | 40 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| houston rockets vs cleveland cavaliers match player stats | 27100 | 34 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| houston rockets vs detroit pistons match player stats | 27100 | 40 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| houston rockets vs knicks match player stats | 27100 | 35 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| houston rockets vs milwaukee bucks match player stats | 27100 | 33 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| houston rockets vs new orleans pelicans match player stats | 27100 | 36 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| knicks vs brooklyn nets match player stats | 27100 | 26 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| knicks vs denver nuggets match player stats | 27100 | 39 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| knicks vs miami heat match player stats | 27100 | 34 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| la clippers vs 76ers match player stats | 27100 | 36 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| la clippers vs dallas mavericks match player stats | 27100 | 34 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| memphis grizzlies vs san antonio spurs match player stats | 27100 | 33 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| phoenix suns vs timberwolves match player stats | 27100 | 39 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| portland trail blazers vs celtics match player stats | 27100 | 37 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| portland trail blazers vs houston rockets match player stats | 27100 | 32 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| portland trail blazers vs new orleans pelicans match player stats | 27100 | 38 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| portland trail blazers vs oklahoma city thunder match player stats | 27100 | 38 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| sacramento kings vs houston rockets match player stats | 27100 | 40 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| sacramento kings vs portland trail blazers match player stats | 27100 | 39 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| sacramento kings vs san antonio spurs match player stats | 27100 | 27 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| san antonio spurs vs atlanta hawks match player stats | 27100 | 25 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| san antonio spurs vs charlotte hornets match player stats | 27100 | 30 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| san antonio spurs vs chicago bulls match player stats | 27100 | 27 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| timberwolves vs 76ers match player stats | 27100 | 38 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| 76ers vs la clippers match player stats | 22200 | 36 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| atlanta hawks vs memphis grizzlies match player stats | 22200 | 26 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| atlanta hawks vs toronto raptors match player stats | 22200 | 36 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| brooklyn nets vs houston rockets match player stats | 22200 | 26 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| brooklyn nets vs orlando magic match player stats | 22200 | 40 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| celtics vs washington wizards match player stats | 22200 | 31 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| charlotte hornets vs cleveland cavaliers match player stats | 22200 | 33 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| charlotte hornets vs dallas mavericks match player stats | 22200 | 36 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| charlotte hornets vs denver nuggets match player stats | 22200 | 39 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| charlotte hornets vs timberwolves match player stats | 22200 | 26 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| charlotte hornets vs washington wizards match player stats | 22200 | 34 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| golden state warriors vs knicks match player stats | 22200 | 27 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| golden state warriors vs miami heat match player stats | 22200 | 34 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| golden state warriors vs new orleans pelicans match player stats | 22200 | 34 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| golden state warriors vs toronto raptors match player stats | 22200 | 40 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| golden state warriors vs washington wizards match player stats | 22200 | 33 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| houston rockets vs 76ers match player stats | 22200 | 35 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| houston rockets vs memphis grizzlies match player stats | 22200 | 37 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| houston rockets vs pacers match player stats | 22200 | 40 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| houston rockets vs portland trail blazers match player stats | 22200 | 36 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| knicks vs charlotte hornets match player stats | 22200 | 40 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| knicks vs la clippers match player stats | 22200 | 37 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| la clippers vs charlotte hornets match player stats | 22200 | 37 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| la clippers vs memphis grizzlies match player stats | 22200 | 36 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| la clippers vs oklahoma city thunder match player stats | 22200 | 36 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| la clippers vs san antonio spurs match player stats | 22200 | 39 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| la clippers vs toronto raptors match player stats | 22200 | 35 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| memphis grizzlies vs knicks match player stats | 22200 | 26 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| memphis grizzlies vs new orleans pelicans match player stats | 22200 | 40 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| memphis grizzlies vs sacramento kings match player stats | 22200 | 37 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| phoenix suns vs 76ers match player stats | 22200 | 38 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| phoenix suns vs charlotte hornets match player stats | 22200 | 26 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| phoenix suns vs new orleans pelicans match player stats | 22200 | 32 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| phoenix suns vs sacramento kings match player stats | 22200 | 35 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| portland trail blazers vs knicks match player stats | 22200 | 36 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| portland trail blazers vs timberwolves match player stats | 22200 | 35 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| sacramento kings vs memphis grizzlies match player stats | 22200 | 38 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| san antonio spurs vs 76ers match player stats | 22200 | 33 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| san antonio spurs vs celtics match player stats | 22200 | 31 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| san antonio spurs vs miami heat match player stats | 22200 | 34 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| san antonio spurs vs washington wizards match player stats | 22200 | 34 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| timberwolves vs celtics match player stats | 22200 | 36 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| timberwolves vs dallas mavericks match player stats | 22200 | 40 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| timberwolves vs detroit pistons match player stats | 22200 | 36 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| 76ers vs brooklyn nets match player stats | 18100 | 36 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| 76ers vs golden state warriors match player stats | 18100 | 38 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| 76ers vs houston rockets match player stats | 18100 | 39 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| 76ers vs miami heat match player stats | 18100 | 40 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| 76ers vs phoenix suns match player stats | 18100 | 37 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| atlanta hawks vs brooklyn nets match player stats | 18100 | 36 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| atlanta hawks vs chicago bulls match player stats | 18100 | 30 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| atlanta hawks vs houston rockets match player stats | 18100 | 34 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| atlanta hawks vs miami heat match player stats | 18100 | 35 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| atlanta hawks vs milwaukee bucks match player stats | 18100 | 40 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| atlanta hawks vs oklahoma city thunder match player stats | 18100 | 37 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| brooklyn nets vs charlotte hornets match player stats | 18100 | 35 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| brooklyn nets vs cleveland cavaliers match player stats | 18100 | 37 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| celtics vs charlotte hornets match player stats | 18100 | 34 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| celtics vs denver nuggets match player stats | 18100 | 39 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| celtics vs memphis grizzlies match player stats | 18100 | 26 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| charlotte hornets vs chicago bulls match player stats | 18100 | 37 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| charlotte hornets vs houston rockets match player stats | 18100 | 37 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| charlotte hornets vs phoenix suns match player stats | 18100 | 26 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| charlotte hornets vs san antonio spurs match player stats | 18100 | 35 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| charlotte hornets vs utah jazz match player stats | 18100 | 38 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| golden state warriors vs memphis grizzlies match player stats | 18100 | 39 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| houston rockets vs brooklyn nets match player stats | 18100 | 26 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| houston rockets vs charlotte hornets match player stats | 18100 | 32 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| houston rockets vs miami heat match player stats | 18100 | 26 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| houston rockets vs orlando magic match player stats | 18100 | 26 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| knicks vs utah jazz match player stats | 18100 | 36 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| la clippers vs celtics match player stats | 18100 | 38 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| la clippers vs detroit pistons match player stats | 18100 | 31 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| la clippers vs knicks match player stats | 18100 | 38 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| la clippers vs new orleans pelicans match player stats | 18100 | 33 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| memphis grizzlies vs cleveland cavaliers match player stats | 18100 | 30 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| memphis grizzlies vs houston rockets match player stats | 18100 | 37 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| memphis grizzlies vs orlando magic match player stats | 18100 | 31 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| pacers vs memphis grizzlies match player stats | 18100 | 34 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| pacers vs orlando magic match player stats | 18100 | 38 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| phoenix suns vs dallas mavericks match player stats | 18100 | 36 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| phoenix suns vs detroit pistons match player stats | 18100 | 40 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| portland trail blazers vs charlotte hornets match player stats | 18100 | 35 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| portland trail blazers vs cleveland cavaliers match player stats | 18100 | 37 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| portland trail blazers vs sacramento kings match player stats | 18100 | 39 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| sacramento kings vs 76ers match player stats | 18100 | 36 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| sacramento kings vs charlotte hornets match player stats | 18100 | 27 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| sacramento kings vs chicago bulls match player stats | 18100 | 34 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| sacramento kings vs pacers match player stats | 18100 | 37 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| san antonio spurs vs cleveland cavaliers match player stats | 18100 | 32 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| san antonio spurs vs pacers match player stats | 18100 | 33 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| san antonio spurs vs toronto raptors match player stats | 18100 | 32 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| team collier vs team clark match player stats | 18100 | 24 | 0 | cap_P1 | 特定篮球赛事的球员数据表，展示双方阵容、得分、篮板、助攻等统计并支持排序。 |
| 76ers vs denver nuggets match player stats | 14800 | 36 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| 76ers vs oklahoma city thunder match player stats | 14800 | 38 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| 76ers vs timberwolves match player stats | 14800 | 38 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| 76ers vs toronto raptors match player stats | 14800 | 34 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| atlanta hawks vs dallas mavericks match player stats | 14800 | 28 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| atlanta hawks vs phoenix suns match player stats | 14800 | 27 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| atlanta hawks vs timberwolves match player stats | 14800 | 36 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| brooklyn nets vs chicago bulls match player stats | 14800 | 39 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| brooklyn nets vs milwaukee bucks match player stats | 14800 | 32 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| brooklyn nets vs timberwolves match player stats | 14800 | 40 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| celtics vs sacramento kings match player stats | 14800 | 36 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| celtics vs toronto raptors match player stats | 14800 | 36 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| charlotte hornets vs brooklyn nets match player stats | 14800 | 39 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| charlotte hornets vs new orleans pelicans match player stats | 14800 | 32 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| golden state warriors vs detroit pistons match player stats | 14800 | 33 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| houston rockets vs atlanta hawks match player stats | 14800 | 38 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| houston rockets vs chicago bulls match player stats | 14800 | 39 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| knicks vs houston rockets match player stats | 14800 | 34 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| knicks vs new orleans pelicans match player stats | 14800 | 36 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| knicks vs phoenix suns match player stats | 14800 | 32 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| knicks vs sacramento kings match player stats | 14800 | 35 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| knicks vs washington wizards match player stats | 14800 | 38 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| la clippers vs atlanta hawks match player stats | 14800 | 30 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| la clippers vs orlando magic match player stats | 14800 | 33 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| la clippers vs pacers match player stats | 14800 | 36 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| memphis grizzlies vs 76ers match player stats | 14800 | 34 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| memphis grizzlies vs celtics match player stats | 14800 | 26 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| memphis grizzlies vs phoenix suns match player stats | 14800 | 33 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| pacers vs new orleans pelicans match player stats | 14800 | 36 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| pacers vs utah jazz match player stats | 14800 | 34 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| pacers vs washington wizards match player stats | 14800 | 30 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| phoenix suns vs atlanta hawks match player stats | 14800 | 29 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| phoenix suns vs brooklyn nets match player stats | 14800 | 37 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| phoenix suns vs knicks match player stats | 14800 | 32 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| phoenix suns vs memphis grizzlies match player stats | 14800 | 33 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| phoenix suns vs miami heat match player stats | 14800 | 33 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| portland trail blazers vs 76ers match player stats | 14800 | 39 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| portland trail blazers vs dallas mavericks match player stats | 14800 | 39 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| sacramento kings vs cleveland cavaliers match player stats | 14800 | 29 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| sacramento kings vs detroit pistons match player stats | 14800 | 35 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| sacramento kings vs knicks match player stats | 14800 | 40 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| san antonio spurs vs milwaukee bucks match player stats | 14800 | 35 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| san antonio spurs vs orlando magic match player stats | 14800 | 37 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| san antonio spurs vs utah jazz match player stats | 14800 | 38 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| team world basketball vs team usa stars match player stats | 14800 | 31 | 0 | cap_P1 | 特定篮球赛事的球员数据表，展示双方阵容、得分、篮板、助攻等统计并支持排序。 |
| timberwolves vs brooklyn nets match player stats | 14800 | 40 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| timberwolves vs charlotte hornets match player stats | 14800 | 26 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| timberwolves vs chicago bulls match player stats | 14800 | 30 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| 76ers vs new orleans pelicans match player stats | 12100 | 34 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| 76ers vs portland trail blazers match player stats | 12100 | 38 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| atlanta hawks vs new orleans pelicans match player stats | 12100 | 40 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| atlanta hawks vs san antonio spurs match player stats | 12100 | 24 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| atlanta hawks vs utah jazz match player stats | 12100 | 39 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| boston celtics vs orlando magic match player stats | 12100 | 40 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| brooklyn nets vs golden state warriors match player stats | 12100 | 33 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| brooklyn nets vs miami heat match player stats | 12100 | 37 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| celtics vs new orleans pelicans match player stats | 12100 | 34 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| charlotte hornets vs portland trail blazers match player stats | 12100 | 38 | 0 | cap_P2 | 球队对阵页，展示最近比赛的球员得分、篮板、助攻等可排序数据，并可切换历史交锋场次。 |
| knicks vs dallas mavericks match player stats | 12100 | 30 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| knicks vs memphis grizzlies match player stats | 12100 | 33 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| knicks vs oklahoma city thunder match player stats | 12100 | 35 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| knicks vs timberwolves match player stats | 12100 | 39 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| la clippers vs chicago bulls match player stats | 12100 | 34 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| la clippers vs cleveland cavaliers match player stats | 12100 | 37 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| las vegas aces vs minnesota lynx match player stats | 12100 | 26 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| los angeles sparks vs golden state valkyries match player stats | 12100 | 23 | 0 | cap_P2 | 按球队对阵聚合的球员数据页，提供可排序表格、关键球员筛选和赛后/赛中状态说明。 |
| pacers vs timberwolves match player stats | 12100 | 36 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| pacers vs toronto raptors match player stats | 12100 | 35 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| phoenix suns vs orlando magic match player stats | 12100 | 28 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| phoenix suns vs pacers match player stats | 12100 | 34 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| phoenix suns vs utah jazz match player stats | 12100 | 39 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| portland trail blazers vs miami heat match player stats | 12100 | 36 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| portland trail blazers vs orlando magic match player stats | 12100 | 35 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| portland trail blazers vs washington wizards match player stats | 12100 | 24 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |
| sacramento kings vs celtics match player stats | 12100 | 37 | 0 | cap_P2 | 按球队对阵聚合的球员数据表，支持排序、筛选、历史场次切换和关键统计对比。 |

## P1 - NBA 球队伤病报告追踪

- Canonical key: tracker/single_entity/team_injury_report/status_table/team
- Badges: Supply=periodic_public_data; Freshness=periodic; Control=weak; Winner=official_source; Permutation=medium
- 页面形态：球队伤病状态表，按球员、伤病类型、出战状态、更新时间和来源展示。
- 变现方式：广告、幻想体育 affiliate、提醒订阅。
- 为什么值得复核：Priority derived from semantic evidence.
- 关键词条目数：1；总搜索量：14800；最高 CPC：3.25

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| timberwolves injury report | 14800 | 38 | 3.25 | none | 球队伤病状态表，按球员、伤病类型、出战状态、更新时间和来源展示。 |

## P1 - NBA 对阵球员数据页

- Canonical key: lookup/entity_pair/event_player_stats/sortable_data_page/team_pair
- Badges: Supply=periodic_public_data; Freshness=event_bound; Control=medium; Winner=specialized_data_provider; Permutation=high
- 页面形态：按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。
- 变现方式：展示广告、体育数据订阅导流、赛程或票务联盟链接
- 为什么值得复核：Priority derived from semantic evidence; cap applied: natural winner is strong, but independent differentiation is credible.
- 关键词条目数：62；总搜索量：1607200；最高 CPC：2.03

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| toronto raptors vs cleveland cavaliers match player stats | 165000 | 39 | 2.03 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| washington wizards vs milwaukee bucks match player stats | 60500 | 36 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| timberwolves vs houston rockets match player stats | 49500 | 28 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| washington wizards vs dallas mavericks match player stats | 49500 | 31 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| washington wizards vs detroit pistons match player stats | 49500 | 39 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| timberwolves vs memphis grizzlies match player stats | 40500 | 38 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| timberwolves vs portland trail blazers match player stats | 40500 | 35 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| toronto raptors vs 76ers match player stats | 40500 | 39 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| utah jazz vs dallas mavericks match player stats | 40500 | 36 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| utah jazz vs golden state warriors match player stats | 40500 | 39 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| washington wizards vs lakers match player stats | 40500 | 38 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| toronto raptors vs lakers match player stats | 33100 | 37 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| toronto raptors vs san antonio spurs match player stats | 33100 | 32 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| utah jazz vs oklahoma city thunder match player stats | 33100 | 35 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| washington wizards vs knicks match player stats | 33100 | 39 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| toronto raptors vs knicks match player stats | 27100 | 35 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| utah jazz vs houston rockets match player stats | 27100 | 38 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| utah jazz vs la clippers match player stats | 27100 | 39 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| utah jazz vs memphis grizzlies match player stats | 27100 | 34 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| utah jazz vs phoenix suns match player stats | 27100 | 38 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| washington wizards vs 76ers match player stats | 27100 | 39 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| washington wizards vs celtics match player stats | 27100 | 36 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| washington wizards vs denver nuggets match player stats | 27100 | 30 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| timberwolves vs new orleans pelicans match player stats | 22200 | 36 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| timberwolves vs san antonio spurs match player stats | 22200 | 40 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| timberwolves vs utah jazz match player stats | 22200 | 36 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| toronto raptors vs charlotte hornets match player stats | 22200 | 32 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| toronto raptors vs dallas mavericks match player stats | 22200 | 29 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| washington wizards vs charlotte hornets match player stats | 22200 | 35 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| washington wizards vs cleveland cavaliers match player stats | 22200 | 35 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| timberwolves vs milwaukee bucks match player stats | 18100 | 34 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| timberwolves vs orlando magic match player stats | 18100 | 24 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| timberwolves vs phoenix suns match player stats | 18100 | 37 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| timberwolves vs sacramento kings match player stats | 18100 | 34 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| toronto raptors vs atlanta hawks match player stats | 18100 | 34 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| toronto raptors vs miami heat match player stats | 18100 | 30 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| toronto raptors vs oklahoma city thunder match player stats | 18100 | 39 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| toronto raptors vs pacers match player stats | 18100 | 28 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| utah jazz vs boston celtics match player stats | 18100 | 40 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| utah jazz vs knicks match player stats | 18100 | 34 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| utah jazz vs portland trail blazers match player stats | 18100 | 29 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| timberwolves vs knicks match player stats | 14800 | 39 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| timberwolves vs miami heat match player stats | 14800 | 30 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| toronto raptors vs denver nuggets match player stats | 14800 | 32 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| toronto raptors vs washington wizards match player stats | 14800 | 34 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| utah jazz vs cleveland cavaliers match player stats | 14800 | 33 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| utah jazz vs denver nuggets match player stats | 14800 | 40 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| utah jazz vs detroit pistons match player stats | 14800 | 28 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| washington wizards vs brooklyn nets match player stats | 14800 | 29 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| washington wizards vs oklahoma city thunder match player stats | 14800 | 32 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| washington wizards vs orlando magic match player stats | 14800 | 27 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| washington wizards vs sacramento kings match player stats | 14800 | 40 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| washington wizards vs san antonio spurs match player stats | 14800 | 34 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| toronto raptors vs brooklyn nets match player stats | 12100 | 35 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| toronto raptors vs orlando magic match player stats | 12100 | 39 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| toronto raptors vs timberwolves match player stats | 12100 | 40 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| utah jazz vs 76ers match player stats | 12100 | 40 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| utah jazz vs brooklyn nets match player stats | 12100 | 31 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| utah jazz vs washington wizards match player stats | 12100 | 26 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| washington wizards vs golden state warriors match player stats | 12100 | 29 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| washington wizards vs houston rockets match player stats | 12100 | 37 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |
| washington wizards vs phoenix suns match player stats | 12100 | 32 | 0 | cap_P1 | 按球队对阵聚合的球员数据页，提供得分、篮板、助攻等字段排序、筛选和历史场次切换。 |

## P1 - 篮球场尺寸查询

- Canonical key: lookup/none/basketball_court_dimensions/interactive_diagram_unit_table/court_standard_or_unit
- Badges: Supply=stable_public_data; Freshness=low; Control=strong; Winner=independent_tool; Permutation=low
- 页面形态：交互式篮球场尺寸图，支持 NBA/FIBA/高中标准切换、英制公制换算和可下载示意图。
- 变现方式：广告、训练器材/场地标线 affiliate、可下载模板。
- 为什么值得复核：Priority derived from semantic evidence.
- 关键词条目数：1；总搜索量：12100；最高 CPC：0.45

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| basketball court dimensions | 12100 | 35 | 0.45 | none | 交互式篮球场尺寸图，支持 NBA/FIBA/高中标准切换、英制公制换算和可下载示意图。 |

## P2 - 球队对阵统计查询

- Canonical key: lookup/entity_pair/team_matchup_stats/comparison_stats_table/team_a_vs_team_b
- Badges: Supply=periodic_public_data; Freshness=event_bound; Control=weak; Winner=specialized_data_provider; Permutation=high
- 页面形态：球队对阵统计页，汇总最近比赛、历史交锋、球队和球员关键指标，并支持筛选赛季。
- 变现方式：广告、体育数据订阅导流、相关球队页面内链。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: high permutation inflation with weak/unknown canonical supply.
- 关键词条目数：1；总搜索量：14800；最高 CPC：4.84

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| celtics vs 76ers stats | 14800 | 40 | 4.84 | cap_P2 | 球队对阵统计页，汇总最近比赛、历史交锋、球队和球员关键指标，并支持筛选赛季。 |

## P2 - NBA 球队深度图查询

- Canonical key: lookup/single_entity/team_depth_chart/depth_chart_table/team
- Badges: Supply=live_external_data; Freshness=periodic; Control=weak; Winner=specialized_data_provider; Permutation=medium
- 页面形态：球队深度图数据页，按位置展示首发、轮换、替补和伤停影响，并标注更新时间。
- 变现方式：广告、fantasy 工具订阅、体育数据订阅。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: dynamic or official data with weak/unknown supply control.
- 关键词条目数：1；总搜索量：18100；最高 CPC：3.35

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| nuggets depth chart | 18100 | 37 | 3.35 | cap_P2 | 球队深度图数据页，按位置展示首发、轮换、替补和伤停影响，并标注更新时间。 |

## P2 - NBA 对阵观看渠道查询

- Canonical key: lookup/entity_pair/broadcast_streaming_availability/availability_table/team_pair_plus_user_location
- Badges: Supply=official_or_marketplace_inventory; Freshness=event_bound; Control=weak; Winner=official_source; Permutation=high
- 页面形态：按用户地区和已有订阅筛选的观看渠道表，展示电视台、流媒体、开赛时间和可用性说明。
- 变现方式：展示广告、流媒体联盟链接、票务或赛程导流
- 为什么值得复核：Priority derived from semantic evidence; cap applied: dynamic or official data with weak/unknown supply control; high permutation inflation with weak/unknown canonical supply.
- 关键词条目数：23；总搜索量：625200；最高 CPC：2.29

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| where to watch pacers vs knicks | 22200 | 31 | 2.29 | cap_P2 | 按用户地区和已有订阅筛选的观看渠道表，展示电视台、流媒体、开赛时间和可用性说明。 |
| where to watch cleveland cavaliers vs pacers | 22200 | 34 | 1.91 | cap_P2 | 按用户地区和已有订阅筛选的观看渠道表，展示电视台、流媒体、开赛时间和可用性说明。 |
| where to watch 76ers vs boston celtics | 18100 | 27 | 1.84 | cap_P2 | 按用户地区和已有订阅筛选的观看渠道表，展示电视台、流媒体、开赛时间和可用性说明。 |
| where to watch okc thunder vs denver nuggets | 14800 | 35 | 1.8 | cap_P2 | 按用户地区和已有订阅筛选的观看渠道表，展示电视台、流媒体、开赛时间和可用性说明。 |
| where to watch houston rockets vs lakers | 60500 | 29 | 1.75 | cap_P2 | 按用户地区和已有订阅筛选的观看渠道表，展示电视台、流媒体、开赛时间和可用性说明。 |
| where to watch portland trail blazers vs san antonio spurs | 33100 | 34 | 1.7 | cap_P2 | 按用户地区和已有订阅筛选的观看渠道表，展示电视台、流媒体、开赛时间和可用性说明。 |
| where to watch cleveland cavaliers vs toronto raptors | 14800 | 26 | 1.7 | cap_P2 | 按用户地区和已有订阅筛选的观看渠道表，展示电视台、流媒体、开赛时间和可用性说明。 |
| where to watch denver nuggets vs oklahoma city thunder | 14800 | 33 | 1.7 | cap_P2 | 按用户地区和已有订阅筛选的观看渠道表，展示电视台、流媒体、开赛时间和可用性说明。 |
| where to watch knicks vs atlanta hawks | 27100 | 34 | 1.6 | cap_P2 | 按用户地区和已有订阅筛选的观看渠道表，展示电视台、流媒体、开赛时间和可用性说明。 |
| where to watch orlando magic vs detroit pistons | 60500 | 33 | 1.56 | cap_P2 | 按用户地区和已有订阅筛选的观看渠道表，展示电视台、流媒体、开赛时间和可用性说明。 |
| where to watch denver nuggets vs timberwolves | 49500 | 28 | 1.56 | cap_P2 | 按用户地区和已有订阅筛选的观看渠道表，展示电视台、流媒体、开赛时间和可用性说明。 |
| where to watch lakers vs oklahoma city thunder | 12100 | 38 | 1.48 | cap_P2 | 按用户地区和已有订阅筛选的观看渠道表，展示电视台、流媒体、开赛时间和可用性说明。 |
| where to watch pacers vs cleveland cavaliers | 12100 | 32 | 1.46 | cap_P2 | 按用户地区和已有订阅筛选的观看渠道表，展示电视台、流媒体、开赛时间和可用性说明。 |
| where to watch atlanta hawks vs knicks | 49500 | 36 | 1.42 | cap_P2 | 按用户地区和已有订阅筛选的观看渠道表，展示电视台、流媒体、开赛时间和可用性说明。 |
| where to watch charlotte hornets vs orlando magic | 14800 | 27 | 1.42 | cap_P2 | 按用户地区和已有订阅筛选的观看渠道表，展示电视台、流媒体、开赛时间和可用性说明。 |
| where to watch golden state warriors vs lakers | 12100 | 32 | 1.41 | cap_P2 | 按用户地区和已有订阅筛选的观看渠道表，展示电视台、流媒体、开赛时间和可用性说明。 |
| where to watch celtics vs 76ers | 49500 | 29 | 1.37 | cap_P2 | 按用户地区和已有订阅筛选的观看渠道表，展示电视台、流媒体、开赛时间和可用性说明。 |
| where to watch oklahoma city thunder vs denver nuggets | 12100 | 33 | 1.36 | cap_P2 | 按用户地区和已有订阅筛选的观看渠道表，展示电视台、流媒体、开赛时间和可用性说明。 |
| where to watch knicks vs pacers | 22200 | 32 | 1.25 | cap_P2 | 按用户地区和已有订阅筛选的观看渠道表，展示电视台、流媒体、开赛时间和可用性说明。 |
| where to watch golden state warriors vs phoenix suns | 14800 | 33 | 0.99 | cap_P2 | 按用户地区和已有订阅筛选的观看渠道表，展示电视台、流媒体、开赛时间和可用性说明。 |
| where to watch minnesota timberwolves vs oklahoma city thunder | 33100 | 27 | 0 | cap_P2 | 按用户地区和已有订阅筛选的观看渠道表，展示电视台、流媒体、开赛时间和可用性说明。 |
| where to watch oklahoma city thunder vs indiana pacers | 33100 | 40 | 0 | cap_P2 | 按用户地区和已有订阅筛选的观看渠道表，展示电视台、流媒体、开赛时间和可用性说明。 |
| where to watch denver nuggets vs okc thunder | 22200 | 29 | 0 | cap_P2 | 按用户地区和已有订阅筛选的观看渠道表，展示电视台、流媒体、开赛时间和可用性说明。 |

## P2 - 球员当晚出战状态检查

- Canonical key: checker/entity_date/player_availability/status_panel/player_tonight
- Badges: Supply=live_external_data; Freshness=live; Control=weak; Winner=official_source; Permutation=high
- 页面形态：球员出战状态检查页，展示今晚比赛、最新状态、消息时间戳和来源摘要。
- 变现方式：广告、体育数据工具订阅导流或合规提醒服务。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: dynamic or official data with weak/unknown supply control; live freshness with high/unknown maintenance burden; high permutation inflation with weak/unknown canonical supply.
- 关键词条目数：2；总搜索量：37000；最高 CPC：2.15

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| is steph curry playing tonight | 22200 | 39 | 2.15 | cap_P2 | 球员出战状态检查页，展示今晚比赛、最新状态、消息时间戳和来源摘要。 |
| is wemby playing tonight | 14800 | 38 | 0 | cap_P2 | 球员出战状态检查页，展示今晚比赛、最新状态、消息时间戳和来源摘要。 |

## P2 - NBA 对阵球员数据查询

- Canonical key: lookup/entity_pair/event_player_stats/sortable_data_page/team_vs_team
- Badges: Supply=periodic_public_data; Freshness=event_bound; Control=weak; Winner=specialized_data_provider; Permutation=high
- 页面形态：球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。
- 变现方式：广告、体育数据订阅、赛事票务或周边联盟。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: high permutation inflation with weak/unknown canonical supply.
- 关键词条目数：97；总搜索量：2827900；最高 CPC：1.69

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| orlando magic vs 76ers match player stats | 110000 | 36 | 1.69 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| orlando magic vs timberwolves match player stats | 18100 | 27 | 1.25 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| orlando magic vs charlotte hornets match player stats | 40500 | 29 | 1.16 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| oklahoma city thunder vs phoenix suns match player stats | 201000 | 36 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| oklahoma city thunder vs lakers match player stats | 110000 | 37 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| oklahoma city thunder vs minnesota timberwolves match player stats | 110000 | 40 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| milwaukee bucks vs 76ers match player stats | 74000 | 36 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| milwaukee bucks vs toronto raptors match player stats | 74000 | 33 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| miami heat vs orlando magic match player stats | 60500 | 40 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| new orleans pelicans vs lakers match player stats | 49500 | 37 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| oklahoma city thunder vs portland trail blazers match player stats | 49500 | 37 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| pacers vs charlotte hornets match player stats | 49500 | 39 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| miami heat vs lakers match player stats | 40500 | 40 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| milwaukee bucks vs oklahoma city thunder match player stats | 40500 | 36 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| milwaukee bucks vs washington wizards match player stats | 40500 | 36 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| oklahoma city thunder vs la clippers match player stats | 40500 | 40 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| oklahoma city thunder vs utah jazz match player stats | 40500 | 35 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| miami heat vs detroit pistons match player stats | 33100 | 34 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| miami heat vs san antonio spurs match player stats | 33100 | 34 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| miami heat vs washington wizards match player stats | 33100 | 40 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| milwaukee bucks vs dallas mavericks match player stats | 33100 | 34 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| milwaukee bucks vs golden state warriors match player stats | 33100 | 34 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| new orleans pelicans vs dallas mavericks match player stats | 33100 | 36 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| new orleans pelicans vs san antonio spurs match player stats | 33100 | 36 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| oklahoma city thunder vs knicks match player stats | 33100 | 36 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| orlando magic vs celtics match player stats | 33100 | 37 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| orlando magic vs cleveland cavaliers match player stats | 33100 | 37 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| orlando magic vs knicks match player stats | 33100 | 39 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| orlando magic vs lakers match player stats | 33100 | 38 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| miami heat vs 76ers match player stats | 27100 | 39 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| miami heat vs toronto raptors match player stats | 27100 | 34 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| milwaukee bucks vs atlanta hawks match player stats | 27100 | 38 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| milwaukee bucks vs charlotte hornets match player stats | 27100 | 25 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| milwaukee bucks vs detroit pistons match player stats | 27100 | 37 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| milwaukee bucks vs orlando magic match player stats | 27100 | 35 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| milwaukee bucks vs san antonio spurs match player stats | 27100 | 34 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| new orleans pelicans vs houston rockets match player stats | 27100 | 38 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| new orleans pelicans vs oklahoma city thunder match player stats | 27100 | 37 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| new orleans pelicans vs timberwolves match player stats | 27100 | 31 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| oklahoma city thunder vs memphis grizzlies match player stats | 27100 | 38 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| oklahoma city thunder vs sacramento kings match player stats | 27100 | 34 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| orlando magic vs golden state warriors match player stats | 27100 | 27 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| pacers vs 76ers match player stats | 27100 | 36 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| miami heat vs chicago bulls match player stats | 22200 | 34 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| miami heat vs cleveland cavaliers match player stats | 22200 | 31 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| miami heat vs denver nuggets match player stats | 22200 | 40 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| miami heat vs pacers match player stats | 22200 | 35 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| milwaukee bucks vs celtics match player stats | 22200 | 39 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| milwaukee bucks vs timberwolves match player stats | 22200 | 34 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| new orleans pelicans vs denver nuggets match player stats | 22200 | 35 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| new orleans pelicans vs la clippers match player stats | 22200 | 30 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| oklahoma city thunder vs cleveland cavaliers match player stats | 22200 | 38 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| orlando magic vs houston rockets match player stats | 22200 | 26 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| orlando magic vs washington wizards match player stats | 22200 | 30 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| miami heat vs dallas mavericks match player stats | 18100 | 35 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| miami heat vs golden state warriors match player stats | 18100 | 36 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| miami heat vs memphis grizzlies match player stats | 18100 | 29 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| milwaukee bucks vs knicks match player stats | 18100 | 36 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| milwaukee bucks vs memphis grizzlies match player stats | 18100 | 34 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| new orleans pelicans vs 76ers match player stats | 18100 | 34 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| new orleans pelicans vs charlotte hornets match player stats | 18100 | 32 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| new orleans pelicans vs golden state warriors match player stats | 18100 | 34 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| new orleans pelicans vs knicks match player stats | 18100 | 39 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| new orleans pelicans vs sacramento kings match player stats | 18100 | 36 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| oklahoma city thunder vs 76ers match player stats | 18100 | 38 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| oklahoma city thunder vs atlanta hawks match player stats | 18100 | 36 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| oklahoma city thunder vs new orleans pelicans match player stats | 18100 | 35 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| oklahoma city thunder vs washington wizards match player stats | 18100 | 30 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| orlando magic vs dallas mavericks match player stats | 18100 | 30 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| orlando magic vs miami heat match player stats | 18100 | 38 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| orlando magic vs phoenix suns match player stats | 18100 | 30 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| pacers vs atlanta hawks match player stats | 18100 | 33 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| new orleans pelicans vs brooklyn nets match player stats | 14800 | 34 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| new orleans pelicans vs celtics match player stats | 14800 | 36 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| new orleans pelicans vs pacers match player stats | 14800 | 29 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| new orleans pelicans vs phoenix suns match player stats | 14800 | 25 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| new orleans pelicans vs utah jazz match player stats | 14800 | 33 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| new orleans pelicans vs washington wizards match player stats | 14800 | 26 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| oklahoma city thunder vs orlando magic match player stats | 14800 | 33 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| orlando magic vs memphis grizzlies match player stats | 14800 | 33 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| orlando magic vs toronto raptors match player stats | 14800 | 39 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| pacers vs chicago bulls match player stats | 14800 | 32 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| pacers vs denver nuggets match player stats | 14800 | 26 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| memphis grizzlies vs utah jazz match player stats | 12100 | 32 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| miami heat vs brooklyn nets match player stats | 12100 | 37 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| miami heat vs milwaukee bucks match player stats | 12100 | 40 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| miami heat vs utah jazz match player stats | 12100 | 33 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| milwaukee bucks vs houston rockets match player stats | 12100 | 35 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| milwaukee bucks vs new orleans pelicans match player stats | 12100 | 38 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| milwaukee bucks vs phoenix suns match player stats | 12100 | 37 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| milwaukee bucks vs sacramento kings match player stats | 12100 | 34 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| new orleans pelicans vs memphis grizzlies match player stats | 12100 | 39 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| new orleans pelicans vs orlando magic match player stats | 12100 | 33 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| orlando magic vs chicago bulls match player stats | 12100 | 33 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| orlando magic vs oklahoma city thunder match player stats | 12100 | 25 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| orlando magic vs pacers match player stats | 12100 | 34 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |
| pacers vs la clippers match player stats | 12100 | 35 | 0 | cap_P2 | 球队对阵球员数据页，支持按比赛、球员、数据项排序筛选，并汇总最近交锋与比赛上下文。 |

## P2 - 球队对阵球员数据查询

- Canonical key: data_page/entity_pair/event_player_stats/sortable_data_page/team_vs_team
- Badges: Supply=live_external_data; Freshness=event_bound; Control=weak; Winner=official_source; Permutation=high
- 页面形态：球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。
- 变现方式：体育广告、联盟导购、数据工具订阅。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: dynamic or official data with weak/unknown supply control; high permutation inflation with weak/unknown canonical supply.
- 关键词条目数：94；总搜索量：2499400；最高 CPC：0.72

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| chicago bulls vs pacers match player stats | 18100 | 35 | 0.72 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| cleveland cavaliers vs toronto raptors match player stats | 110000 | 40 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| dallas mavericks vs celtics match player stats | 110000 | 34 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| denver nuggets vs san antonio spurs match player stats | 74000 | 32 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| cleveland cavaliers vs detroit pistons match player stats | 49500 | 36 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| dallas mavericks vs memphis grizzlies match player stats | 49500 | 33 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| dallas mavericks vs utah jazz match player stats | 49500 | 36 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| denver nuggets vs portland trail blazers match player stats | 49500 | 36 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| detroit pistons vs cleveland cavaliers match player stats | 49500 | 36 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| detroit pistons vs milwaukee bucks match player stats | 49500 | 37 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| cleveland cavaliers vs orlando magic match player stats | 40500 | 34 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| dallas mavericks vs houston rockets match player stats | 40500 | 32 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| detroit pistons vs 76ers match player stats | 40500 | 32 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| detroit pistons vs charlotte hornets match player stats | 40500 | 38 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| chicago bulls vs lakers match player stats | 33100 | 38 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| chicago bulls vs orlando magic match player stats | 33100 | 34 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| cleveland cavaliers vs chicago bulls match player stats | 33100 | 34 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| cleveland cavaliers vs sacramento kings match player stats | 33100 | 29 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| denver nuggets vs knicks match player stats | 33100 | 35 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| detroit pistons vs chicago bulls match player stats | 33100 | 34 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| chicago bulls vs denver nuggets match player stats | 27100 | 31 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| chicago bulls vs detroit pistons match player stats | 27100 | 37 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| chicago bulls vs knicks match player stats | 27100 | 38 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| cleveland cavaliers vs atlanta hawks match player stats | 27100 | 38 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| cleveland cavaliers vs charlotte hornets match player stats | 27100 | 31 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| cleveland cavaliers vs denver nuggets match player stats | 27100 | 34 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| cleveland cavaliers vs la clippers match player stats | 27100 | 38 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| cleveland cavaliers vs washington wizards match player stats | 27100 | 33 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| dallas mavericks vs detroit pistons match player stats | 27100 | 39 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| dallas mavericks vs portland trail blazers match player stats | 27100 | 31 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| dallas mavericks vs timberwolves match player stats | 27100 | 37 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| denver nuggets vs detroit pistons match player stats | 27100 | 38 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| denver nuggets vs miami heat match player stats | 27100 | 35 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| denver nuggets vs new orleans pelicans match player stats | 27100 | 35 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| denver nuggets vs sacramento kings match player stats | 27100 | 37 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| detroit pistons vs brooklyn nets match player stats | 27100 | 40 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| detroit pistons vs denver nuggets match player stats | 27100 | 39 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| detroit pistons vs golden state warriors match player stats | 27100 | 34 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| detroit pistons vs miami heat match player stats | 27100 | 36 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| detroit pistons vs san antonio spurs match player stats | 27100 | 38 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| golden state warriors vs 76ers match player stats | 27100 | 38 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| golden state warriors vs charlotte hornets match player stats | 27100 | 29 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| chicago bulls vs atlanta hawks match player stats | 22200 | 34 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| chicago bulls vs celtics match player stats | 22200 | 40 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| chicago bulls vs charlotte hornets match player stats | 22200 | 38 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| chicago bulls vs miami heat match player stats | 22200 | 34 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| chicago sky vs washington mystics match player stats | 22200 | 27 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| cleveland cavaliers vs oklahoma city thunder match player stats | 22200 | 32 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| cleveland cavaliers vs phoenix suns match player stats | 22200 | 33 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| cleveland cavaliers vs san antonio spurs match player stats | 22200 | 34 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| dallas mavericks vs cleveland cavaliers match player stats | 22200 | 35 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| dallas mavericks vs knicks match player stats | 22200 | 35 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| dallas mavericks vs sacramento kings match player stats | 22200 | 34 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| dallas mavericks vs washington wizards match player stats | 22200 | 35 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| denver nuggets vs celtics match player stats | 22200 | 35 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| denver nuggets vs charlotte hornets match player stats | 22200 | 34 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| denver nuggets vs cleveland cavaliers match player stats | 22200 | 31 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| detroit pistons vs dallas mavericks match player stats | 22200 | 39 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| detroit pistons vs la clippers match player stats | 22200 | 31 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| detroit pistons vs utah jazz match player stats | 22200 | 28 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| detroit pistons vs washington wizards match player stats | 22200 | 38 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| golden state warriors vs cleveland cavaliers match player stats | 22200 | 34 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| chicago bulls vs cleveland cavaliers match player stats | 18100 | 34 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| cleveland cavaliers vs houston rockets match player stats | 18100 | 38 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| cleveland cavaliers vs milwaukee bucks match player stats | 18100 | 40 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| dallas mavericks vs new orleans pelicans match player stats | 18100 | 33 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| dallas mavericks vs orlando magic match player stats | 18100 | 26 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| denver nuggets vs atlanta hawks match player stats | 18100 | 39 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| denver nuggets vs chicago bulls match player stats | 18100 | 29 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| denver nuggets vs pacers match player stats | 18100 | 27 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| denver nuggets vs toronto raptors match player stats | 18100 | 32 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| detroit pistons vs atlanta hawks match player stats | 18100 | 35 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| detroit pistons vs pacers match player stats | 18100 | 38 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| detroit pistons vs toronto raptors match player stats | 18100 | 35 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| golden state warriors vs brooklyn nets match player stats | 18100 | 37 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| chicago bulls vs 76ers match player stats | 14800 | 34 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| chicago bulls vs brooklyn nets match player stats | 14800 | 32 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| chicago bulls vs utah jazz match player stats | 14800 | 39 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| dallas mavericks vs atlanta hawks match player stats | 14800 | 28 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| dallas mavericks vs charlotte hornets match player stats | 14800 | 37 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| dallas mavericks vs miami heat match player stats | 14800 | 26 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| denver nuggets vs 76ers match player stats | 14800 | 37 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| detroit pistons vs phoenix suns match player stats | 14800 | 32 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| detroit pistons vs timberwolves match player stats | 14800 | 32 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| chicago bulls vs dallas mavericks match player stats | 12100 | 30 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| chicago bulls vs golden state warriors match player stats | 12100 | 35 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| chicago bulls vs houston rockets match player stats | 12100 | 37 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| chicago bulls vs sacramento kings match player stats | 12100 | 39 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| chicago bulls vs timberwolves match player stats | 12100 | 31 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| cleveland cavaliers vs memphis grizzlies match player stats | 12100 | 30 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| denver nuggets vs brooklyn nets match player stats | 12100 | 39 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| denver nuggets vs washington wizards match player stats | 12100 | 34 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| detroit pistons vs sacramento kings match player stats | 12100 | 25 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |
| golden state warriors vs atlanta hawks match player stats | 12100 | 29 | 0 | cap_P2 | 球队对阵球员数据页，支持按球员、球队和统计项排序过滤，并汇总赛后核心数据。 |

## P2 - NBA 夏季联赛赛程查询

- Canonical key: lookup/many_permutations/nba_summer_league_schedule/filterable_schedule_table/league_event
- Badges: Supply=official_or_marketplace_inventory; Freshness=periodic; Control=weak; Winner=official_source; Permutation=medium
- 页面形态：夏季联赛赛程表，支持球队筛选、时区转换、日历订阅、比分状态和提醒。
- 变现方式：广告、日历订阅、赛事票务或周边联盟。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: dynamic or official data with weak/unknown supply control.
- 关键词条目数：1；总搜索量：22200；最高 CPC：0.27

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| nba summer league schedule | 22200 | 33 | 0.27 | cap_P2 | 夏季联赛赛程表，支持球队筛选、时区转换、日历订阅、比分状态和提醒。 |

## P2 - NBA 对阵时间线查询

- Canonical key: lookup/entity_pair/event_timeline/chronological_timeline/team_a_vs_team_b
- Badges: Supply=live_external_data; Freshness=event_bound; Control=weak; Winner=official_source; Permutation=high
- 页面形态：对阵事件时间线，按节次展示比分变化、关键回合和球员事件，并可切换历史场次。
- 变现方式：广告、体育数据 affiliate、会员高级回放视图。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: dynamic or official data with weak/unknown supply control; high permutation inflation with weak/unknown canonical supply.
- 关键词条目数：3；总搜索量：86500；最高 CPC：0

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| pacers vs oklahoma city thunder timeline | 49500 | 32 | 0 | cap_P2 | 对阵事件时间线，按节次展示比分变化、关键回合和球员事件，并可切换历史场次。 |
| san antonio spurs vs oklahoma city thunder timeline | 22200 | 39 | 0 | cap_P2 | 对阵事件时间线，按节次展示比分变化、关键回合和球员事件，并可切换历史场次。 |
| san antonio spurs vs golden state warriors timeline | 14800 | 35 | 0 | cap_P2 | 对阵事件时间线，按节次展示比分变化、关键回合和球员事件，并可切换历史场次。 |

## P2 - 比赛时间线查询

- Canonical key: data_page/entity_pair/game_timeline/play_by_play_timeline/team_vs_team
- Badges: Supply=live_external_data; Freshness=event_bound; Control=weak; Winner=specialized_data_provider; Permutation=high
- 页面形态：球队对阵比赛时间线页，展示关键节点、比分变化和可筛选的 play-by-play 事件。
- 变现方式：体育广告、数据工具订阅、合规联盟导购。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: dynamic or official data with weak/unknown supply control; high permutation inflation with weak/unknown canonical supply.
- 关键词条目数：5；总搜索量：75500；最高 CPC：0

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| denver nuggets vs oklahoma city thunder timeline | 27100 | 39 | 0 | cap_P2 | 球队对阵比赛时间线页，展示关键节点、比分变化和可筛选的 play-by-play 事件。 |
| cleveland cavaliers vs detroit pistons timeline | 12100 | 40 | 0 | cap_P2 | 球队对阵比赛时间线页，展示关键节点、比分变化和可筛选的 play-by-play 事件。 |
| dallas mavericks vs golden state warriors timeline | 12100 | 38 | 0 | cap_P2 | 球队对阵比赛时间线页，展示关键节点、比分变化和可筛选的 play-by-play 事件。 |
| denver nuggets vs sacramento kings timeline | 12100 | 39 | 0 | cap_P2 | 球队对阵比赛时间线页，展示关键节点、比分变化和可筛选的 play-by-play 事件。 |
| detroit pistons vs pacers timeline | 12100 | 38 | 0 | cap_P2 | 球队对阵比赛时间线页，展示关键节点、比分变化和可筛选的 play-by-play 事件。 |

## P2 - 球队对阵时间线可视化

- Canonical key: data_page/entity_pair/team_matchup_timeline/interactive_timeline/team_a_vs_team_b
- Badges: Supply=periodic_public_data; Freshness=event_bound; Control=weak; Winner=specialized_data_provider; Permutation=high
- 页面形态：球队对阵时间线页，用可视化轴展示历史交锋、单场关键节点或比分变化，并支持筛选。
- 变现方式：广告或体育数据/赛程工具导流。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: high permutation inflation with weak/unknown canonical supply.
- 关键词条目数：4；总搜索量：64500；最高 CPC：0

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| la clippers vs golden state warriors timeline | 22200 | 40 | 0 | cap_P2 | 球队对阵时间线页，用可视化轴展示历史交锋、单场关键节点或比分变化，并支持筛选。 |
| knicks vs orlando magic timeline | 18100 | 34 | 0 | cap_P2 | 球队对阵时间线页，用可视化轴展示历史交锋、单场关键节点或比分变化，并支持筛选。 |
| golden state warriors vs orlando magic timeline | 12100 | 35 | 0 | cap_P2 | 球队对阵时间线页，用可视化轴展示历史交锋、单场关键节点或比分变化，并支持筛选。 |
| knicks vs 76ers timeline | 12100 | 40 | 0 | cap_P2 | 球队对阵时间线页，用可视化轴展示历史交锋、单场关键节点或比分变化，并支持筛选。 |

## P2 - 球队对阵时间线查询

- Canonical key: lookup/entity_pair/matchup_timeline/chronological_timeline/team_a_vs_team_b
- Badges: Supply=periodic_public_data; Freshness=event_bound; Control=weak; Winner=specialized_data_provider; Permutation=high
- 页面形态：球队对阵时间线页，按日期或比赛进程展示关键事件、比分变化和相关数据入口。
- 变现方式：广告、体育数据订阅导流、相关球队页面内链。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: high permutation inflation with weak/unknown canonical supply.
- 关键词条目数：3；总搜索量：42300；最高 CPC：0

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| charlotte hornets vs orlando magic timeline | 18100 | 35 | 0 | cap_P2 | 球队对阵时间线页，按日期或比赛进程展示关键事件、比分变化和相关数据入口。 |
| 76ers vs dallas mavericks timeline | 12100 | 39 | 0 | cap_P2 | 球队对阵时间线页，按日期或比赛进程展示关键事件、比分变化和相关数据入口。 |
| charlotte hornets vs cleveland cavaliers timeline | 12100 | 40 | 0 | cap_P2 | 球队对阵时间线页，按日期或比赛进程展示关键事件、比分变化和相关数据入口。 |

## P2 - NBA 对阵时间线

- Canonical key: lookup/entity_pair/game_timeline/event_timeline/team_pair
- Badges: Supply=periodic_public_data; Freshness=event_bound; Control=weak; Winner=official_source; Permutation=high
- 页面形态：对阵时间线页，按节次或历史交锋展示关键比分变化、事件节点和可筛选的比赛记录。
- 变现方式：展示广告、体育数据导流、赛程相关联盟链接
- 为什么值得复核：Priority derived from semantic evidence; cap applied: high permutation inflation with weak/unknown canonical supply.
- 关键词条目数：3；总搜索量：36300；最高 CPC：0

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| timberwolves vs new orleans pelicans timeline | 12100 | 39 | 0 | cap_P2 | 对阵时间线页，按节次或历史交锋展示关键比分变化、事件节点和可筛选的比赛记录。 |
| utah jazz vs lakers timeline | 12100 | 38 | 0 | cap_P2 | 对阵时间线页，按节次或历史交锋展示关键比分变化、事件节点和可筛选的比赛记录。 |
| washington wizards vs miami heat timeline | 12100 | 31 | 0 | cap_P2 | 对阵时间线页，按节次或历史交锋展示关键比分变化、事件节点和可筛选的比赛记录。 |

## P2 - 球队对阵统计查询

- Canonical key: data_page/entity_pair/team_matchup_stats/comparison_stat_table/team_vs_team
- Badges: Supply=periodic_public_data; Freshness=periodic; Control=weak; Winner=specialized_data_provider; Permutation=high
- 页面形态：球队对阵统计比较页，汇总近期交手、球队数据和可筛选统计表。
- 变现方式：体育广告、联盟导购、数据工具订阅。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: high permutation inflation with weak/unknown canonical supply.
- 关键词条目数：1；总搜索量：12100；最高 CPC：0

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| denver nuggets vs okc thunder stats | 12100 | 36 | 0 | cap_P2 | 球队对阵统计比较页，汇总近期交手、球队数据和可筛选统计表。 |
