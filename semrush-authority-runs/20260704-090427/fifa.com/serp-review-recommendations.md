# SERP 复核推荐词簇

二筛候选来源数：6
推荐词簇数：5
推荐关键词条目数：6

| 优先级 | 词簇数 | 关键词条目数 |
| --- | ---: | ---: |
| P0 | 0 | 0 |
| P1 | 3 | 3 |
| P2 | 2 | 3 |

优先级说明：
- P0：优先复核；供给可控、维护有界、差异化清楚，且不是由排列组合搜索量硬抬上来。
- P1：随后复核；机会成立，但数据供给、自然赢家或执行成本还需要确认。
- P2：长尾、cluster seed 或需数据源确认；不是自动拒绝。

## P1 - 世界杯足球赛程括号生成器

- Canonical key: generator/event_instance/world_cup_bracket/interactive_bracket/event_format_or_user_picks
- Badges: Supply=user_input_transform; Freshness=low; Control=strong; Winner=independent_tool; Permutation=medium
- 页面形态：可交互世界杯晋级图，支持空白模板、用户预测、打印分享和赛果填充。
- 变现方式：广告、打印模板、预测游戏赞助、体育联盟导流。
- 为什么值得复核：Priority derived from semantic evidence.
- 关键词条目数：1；总搜索量：18100；最高 CPC：3.38

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| soccer bracket world cup | 18100 | 30 | 3.38 | none | 可交互世界杯晋级图，支持空白模板、用户预测、打印分享和赛果填充。 |

## P1 - 2025俱乐部世界杯赛程查询

- Canonical key: data_page/event_instance/club_world_cup_match_schedule/filterable_schedule/event_year_language_optional
- Badges: Supply=periodic_public_data; Freshness=event_bound; Control=medium; Winner=official_source; Permutation=medium
- 页面形态：西语赛程表，支持球队、日期、阶段、场地和本地时区筛选，并提供日历订阅。
- 变现方式：广告、票务/转播导流、赛程提醒订阅。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: natural winner is strong, but independent differentiation is credible.
- 关键词条目数：1；总搜索量：14800；最高 CPC：0

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| partidos del mundial de clubes 2025 | 14800 | 40 | 0 | cap_P1 | 西语赛程表，支持球队、日期、阶段、场地和本地时区筛选，并提供日历订阅。 |

## P1 - 俱乐部世界杯积分榜追踪器

- Canonical key: data_page/event_instance/club_world_cup_standings/sortable_standings_table/event_year_or_stage_optional
- Badges: Supply=periodic_public_data; Freshness=event_bound; Control=medium; Winner=official_source; Permutation=medium
- 页面形态：可排序积分榜，按小组、阶段、年份切换，并联动晋级路径和赛程结果。
- 变现方式：广告、体育数据联盟、赛程提醒订阅。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: natural winner is strong, but independent differentiation is credible.
- 关键词条目数：1；总搜索量：14800；最高 CPC：0

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| club world cup standings | 14800 | 39 | 0 | cap_P1 | 可排序积分榜，按小组、阶段、年份切换，并联动晋级路径和赛程结果。 |

## P2 - 球队对阵比赛数据页

- Canonical key: data_page/entity_pair/team_match_stats/stat_comparison_table/team_a_vs_team_b
- Badges: Supply=periodic_public_data; Freshness=event_bound; Control=weak; Winner=specialized_data_provider; Permutation=high
- 页面形态：赛前/赛后球队统计对比表，包含控球、射门、阵容、历史交锋和关键球员维度。
- 变现方式：广告、体育数据联盟、赛前工具导流。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: high permutation inflation with weak/unknown canonical supply.
- 关键词条目数：2；总搜索量：24200；最高 CPC：0

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| fluminense fc vs chelsea f.c. stats | 12100 | 28 | 0 | cap_P2 | 赛前/赛后球队统计对比表，包含控球、射门、阵容、历史交锋和关键球员维度。 |
| man city vs al-hilal sfc stats | 12100 | 30 | 0 | cap_P2 | 对阵统计面板，提供球队数据对比、历史交锋、近期状态、阵容和比赛事件表。 |

## P2 - 比赛观看渠道查询器

- Canonical key: lookup/entity_pair/match_broadcast_availability/geo_channel_table/team_a_vs_team_b_user_location
- Badges: Supply=official_or_marketplace_inventory; Freshness=event_bound; Control=weak; Winner=official_source; Permutation=high
- 页面形态：按国家/地区展示电视频道、流媒体、开赛时间和可用提醒的观看渠道表。
- 变现方式：广告、合法流媒体联盟、赛前提醒订阅。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: dynamic or official data with weak/unknown supply control; high permutation inflation with weak/unknown canonical supply.
- 关键词条目数：1；总搜索量：14800；最高 CPC：0

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| where to watch psg vs inter miami | 14800 | 28 | 0 | cap_P2 | 按国家/地区展示电视频道、流媒体、开赛时间和可用提醒的观看渠道表。 |
