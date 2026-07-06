# SERP 复核推荐词簇

二筛候选来源数：10
推荐词簇数：4
推荐关键词条目数：10

| 优先级 | 词簇数 | 关键词条目数 |
| --- | ---: | ---: |
| P0 | 0 | 0 |
| P1 | 3 | 9 |
| P2 | 1 | 1 |

优先级说明：
- P0：优先复核；供给可控、维护有界、差异化清楚，且不是由排列组合搜索量硬抬上来。
- P1：随后复核；机会成立，但数据供给、自然赢家或执行成本还需要确认。
- P2：长尾、cluster seed 或需数据源确认；不是自动拒绝。

## P1 - 球队赛程查询页

- Canonical key: lookup/single_entity/team_schedule/filterable_schedule_table/team
- Badges: Supply=periodic_public_data; Freshness=periodic; Control=medium; Winner=official_source; Permutation=high
- 页面形态：按球队聚合的赛程数据页，提供日期、对手、主客场、场馆、开赛时间、日历导出、票务入口和可筛选视图。
- 变现方式：票务联盟、广告、日历订阅或球队周边导购。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: natural winner is strong, but independent differentiation is credible.
- 关键词条目数：7；总搜索量：249100；最高 CPC：1.05

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| husker volleyball schedule | 49500 | 40 | 1.05 | cap_P1 | Husker 排球赛程查询页，包含日期、对手、地点、比赛状态、转播信息、日历订阅、票务入口和赛季筛选。 |
| nebraska volleyball schedule | 110000 | 36 | 0.84 | cap_P1 | Nebraska 排球赛程数据页，支持赛季、主客场、转播、结果状态、票务入口、提醒和日历导出。 |
| clemson basketball schedule | 14800 | 34 | 0.69 | cap_P1 | Clemson 篮球赛程页，展示日期、对手、主客场、场馆、电视/直播信息、结果状态、日历导出和购票入口。 |
| utah mammoth schedule | 18100 | 38 | 0.39 | cap_P1 | Utah Mammoth 赛程数据页，提供日期、对手、主客场、场馆、电视/直播、结果状态、票务入口和日历订阅。 |
| philadelphia union schedule | 14800 | 29 | 0.33 | cap_P1 | Philadelphia Union 赛程页，包含比赛日期、对手、主客场、场馆、开赛时间、电视/直播、日历导出和票务入口。 |
| austin fc schedule | 14800 | 34 | 0.3 | cap_P1 | 按球队聚合的赛程数据页，提供日期、对手、主客场、场馆、开赛时间、日历导出、票务入口和可筛选视图。 |
| lsu women's basketball schedule | 27100 | 35 | 0 | cap_P1 | LSU 女篮赛程数据页，提供赛季筛选、日期、对手、主客场、场馆、电视/直播、结果、提醒和日历导出。 |

## P1 - 场馆座位图查询工具

- Canonical key: lookup/single_entity/venue_seating_chart/interactive_map/venue
- Badges: Supply=stable_public_data; Freshness=low; Control=medium; Winner=marketplace; Permutation=medium
- 页面形态：Sphere 互动座位图，支持区域/排/视野筛选、舞台布局切换、可见性说明、价格区间入口和无障碍座位提示。
- 变现方式：票务联盟、广告、酒店/旅行联盟或高级视野数据订阅。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: maintenance burden is medium and supply control is not strong.
- 关键词条目数：1；总搜索量：12100；最高 CPC：0.8

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| sphere seating chart | 12100 | 30 | 0.8 | cap_P1 | Sphere 互动座位图，支持区域/排/视野筛选、舞台布局切换、可见性说明、价格区间入口和无障碍座位提示。 |

## P1 - 年度音乐节发现库

- Canonical key: library/entity_date/music_festival_calendar/filterable_event_directory/year
- Badges: Supply=periodic_public_data; Freshness=periodic; Control=weak; Winner=specialized_data_provider; Permutation=medium
- 页面形态：2026 音乐节可筛选目录，按日期、地点、音乐类型、阵容状态、价格区间、露营/年龄限制和购票入口过滤。
- 变现方式：票务联盟、旅游/酒店联盟、广告或高级提醒订阅。
- 为什么值得复核：Priority derived from semantic evidence.
- 关键词条目数：1；总搜索量：12100；最高 CPC：0.63

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| music festivals 2026 | 12100 | 37 | 0.63 | none | 2026 音乐节可筛选目录，按日期、地点、音乐类型、阵容状态、价格区间、露营/年龄限制和购票入口过滤。 |

## P2 - 赛事观看渠道查询器

- Canonical key: lookup/entity_pair/sports_event_watch_options/availability_panel/team_pair
- Badges: Supply=live_external_data; Freshness=event_bound; Control=weak; Winner=specialized_data_provider; Permutation=high
- 页面形态：赛事观看渠道面板，让用户按地区、电视服务商或流媒体订阅查看 Yankees vs Mariners 的可观看平台、开赛时间、限制和提醒。
- 变现方式：流媒体联盟、广告、体育订阅导购或提醒服务。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: dynamic or official data with weak/unknown supply control; high permutation inflation with weak/unknown canonical supply.
- 关键词条目数：1；总搜索量：12100；最高 CPC：1.56

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| where to watch new york yankees vs seattle mariners | 12100 | 38 | 1.56 | cap_P2 | 赛事观看渠道面板，让用户按地区、电视服务商或流媒体订阅查看 Yankees vs Mariners 的可观看平台、开赛时间、限制和提醒。 |
