# SERP 复核推荐词簇

二筛候选来源数：3
推荐词簇数：2
推荐关键词条目数：3

| 优先级 | 词簇数 | 关键词条目数 |
| --- | ---: | ---: |
| P0 | 0 | 0 |
| P1 | 1 | 2 |
| P2 | 1 | 1 |

优先级说明：
- P0：优先复核；供给可控、维护有界、差异化清楚，且不是由排列组合搜索量硬抬上来。
- P1：随后复核；机会成立，但数据供给、自然赢家或执行成本还需要确认。
- P2：长尾、cluster seed 或需数据源确认；不是自动拒绝。

## P1 - sports team schedule lookup

- Canonical key: lookup/single_entity/sports_team_schedule/calendar_table/team
- Badges: Supply=periodic_public_data; Freshness=periodic; Control=medium; Winner=official_source; Permutation=high
- 页面形态：球队赛程日历页，包含日期、对手、主客场、场馆、当地时间转换、筛选和日历订阅入口。
- 变现方式：广告、票务联盟、酒店/旅行联盟和赛程提醒订阅。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: natural winner is strong, but independent differentiation is credible.
- 关键词条目数：2；总搜索量：88800；最高 CPC：0.44

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| club america schedule | 74000 | 38 | 0.44 | cap_P1 | 球队赛程日历页，包含日期、对手、主客场、场馆、当地时间转换、筛选和日历订阅入口。 |
| vegas golden knights schedule | 14800 | 40 | 0.31 | cap_P1 | 球队赛程数据页，提供日期、对手、主客场、场馆、电视/直播信息、时区切换、筛选和日历订阅。 |

## P2 - artist upcoming events lookup

- Canonical key: lookup/single_entity/artist_event_calendar/event_list/artist
- Badges: Supply=official_or_marketplace_inventory; Freshness=event_bound; Control=weak; Winner=marketplace; Permutation=high
- 页面形态：艺人活动聚合页，按日期和城市列出 upcoming events，提供场馆、票务入口、价格区间、提醒和地图筛选。
- 变现方式：票务联盟、广告、旅行/酒店联盟和活动提醒订阅。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: dynamic or official data with weak/unknown supply control; high permutation inflation with weak/unknown canonical supply.
- 关键词条目数：1；总搜索量：12100；最高 CPC：0.2

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| ella langley upcoming events | 12100 | 32 | 0.2 | cap_P2 | 艺人活动聚合页，按日期和城市列出 upcoming events，提供场馆、票务入口、价格区间、提醒和地图筛选。 |
