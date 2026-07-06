# SERP 复核推荐词簇

二筛候选来源数：14
推荐词簇数：10
推荐关键词条目数：14

| 优先级 | 词簇数 | 关键词条目数 |
| --- | ---: | ---: |
| P0 | 0 | 0 |
| P1 | 3 | 4 |
| P2 | 7 | 10 |

优先级说明：
- P0：优先复核；供给可控、维护有界、差异化清楚，且不是由排列组合搜索量硬抬上来。
- P1：随后复核；机会成立，但数据供给、自然赢家或执行成本还需要确认。
- P2：长尾、cluster seed 或需数据源确认；不是自动拒绝。

## P1 - team_schedule_lookup

- Canonical key: lookup/single_entity/team_schedule/fixture_calendar/team_name
- Badges: Supply=periodic_public_data; Freshness=event_bound; Control=medium; Winner=official_source; Permutation=high
- 页面形态：球队赛程日历页，支持按赛事、主客场、日期过滤，并附直播/票务/日历订阅入口。
- 变现方式：广告、票务联盟、体育内容联盟。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: natural winner is strong, but independent differentiation is credible.
- 关键词条目数：2；总搜索量：88800；最高 CPC：0.44

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| club america schedule | 74000 | 38 | 0.44 | cap_P1 | 球队赛程日历页，支持按赛事、主客场、日期过滤，并附直播/票务/日历订阅入口。 |
| vegas golden knights schedule | 14800 | 40 | 0.31 | cap_P1 | 球队赛程日历页，展示赛程、对手、主客场、电视信息、票务入口和日历订阅。 |

## P1 - team_schedule_lookup

- Canonical key: lookup/single_entity/team_schedule/fixture_calendar/team_name_sport
- Badges: Supply=periodic_public_data; Freshness=event_bound; Control=medium; Winner=official_source; Permutation=high
- 页面形态：球队篮球赛程日历，包含日期、对手、地点、比分状态、电视转播、票务和日历订阅。
- 变现方式：广告、票务联盟、体育内容联盟。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: natural winner is strong, but independent differentiation is credible.
- 关键词条目数：1；总搜索量：18100；最高 CPC：0

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| syracuse basketball schedule | 18100 | 33 | 0 | cap_P1 | 球队篮球赛程日历，包含日期、对手、地点、比分状态、电视转播、票务和日历订阅。 |

## P1 - national_team_games_lookup

- Canonical key: lookup/single_entity/team_schedule/fixture_calendar/national_team_name
- Badges: Supply=periodic_public_data; Freshness=event_bound; Control=medium; Winner=official_source; Permutation=high
- 页面形态：国家队比赛日历页，按赛事类型、日期和地点展示赛程，并提供本地时间、票务和直播信息。
- 变现方式：广告、票务联盟、体育直播/内容联盟。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: natural winner is strong, but independent differentiation is credible.
- 关键词条目数：1；总搜索量：12100；最高 CPC：0

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| guatemala national football team games | 12100 | 36 | 0 | cap_P1 | 国家队比赛日历页，按赛事类型、日期和地点展示赛程，并提供本地时间、票务和直播信息。 |

## P2 - artist_setlist_lookup

- Canonical key: lookup/single_entity/artist_setlist/setlist_history_page/artist_name
- Badges: Supply=subjective_or_ugc; Freshness=event_bound; Control=weak; Winner=community_or_forum; Permutation=high
- 页面形态：艺人 setlist 历史页，按巡演和日期展示曲目、常见开场/返场、变化趋势和播放列表跳转。
- 变现方式：广告、音乐联盟、演出票务联盟。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: high permutation inflation with weak/unknown canonical supply.
- 关键词条目数：3；总搜索量：45000；最高 CPC：2.41

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| morgan wallen setlist | 12100 | 26 | 2.41 | cap_P2 | 艺人 setlist 数据页，汇总近期演出曲目、巡演差异、热门曲目频率和播放列表入口。 |
| jonas brothers setlist | 18100 | 33 | 0 | cap_P2 | 艺人 setlist 历史页，按巡演和日期展示曲目、常见开场/返场、变化趋势和播放列表跳转。 |
| nine inch nails setlist | 14800 | 31 | 0 | cap_P2 | 艺人 setlist 历史查询页，提供巡演、年份、歌曲频率、近期演出曲目和播放列表入口。 |

## P2 - local_performer_event_calendar

- Canonical key: lookup/entity_location/performer_event_calendar/filterable_event_calendar/performer_category_city
- Badges: Supply=live_external_data; Freshness=live; Control=weak; Winner=marketplace; Permutation=high
- 页面形态：纽约喜剧演出日历，按日期、区域、场馆、票价和演员筛选，并提供地图与购票跳转。
- 变现方式：票务联盟、广告、本地演出推广。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: dynamic or official data with weak/unknown supply control; live freshness with high/unknown maintenance burden; high permutation inflation with weak/unknown canonical supply.
- 关键词条目数：1；总搜索量：12100；最高 CPC：1.22

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| comedians performing nyc | 12100 | 33 | 1.22 | cap_P2 | 纽约喜剧演出日历，按日期、区域、场馆、票价和演员筛选，并提供地图与购票跳转。 |

## P2 - team_schedule_lookup

- Canonical key: lookup/single_entity/team_schedule/fixture_calendar/team_alias
- Badges: Supply=periodic_public_data; Freshness=event_bound; Control=unknown; Winner=official_source; Permutation=high
- 页面形态：球队别名赛程查询页，先做实体消歧，再展示赛程、比赛地点、时间和订阅入口。
- 变现方式：广告、票务联盟、体育内容联盟。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: high permutation inflation with weak/unknown canonical supply.
- 关键词条目数：1；总搜索量：12100；最高 CPC：0.45

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| pumas schedule | 12100 | 25 | 0.45 | cap_P2 | 球队别名赛程查询页，先做实体消歧，再展示赛程、比赛地点、时间和订阅入口。 |

## P2 - weekend_activity_planner

- Canonical key: planner/entity_location/weekend_activity_plan/filtered_itinerary_builder/city_relative_date
- Badges: Supply=live_external_data; Freshness=event_bound; Control=weak; Winner=specialized_data_provider; Permutation=high
- 页面形态：周末活动规划器，按兴趣、预算、时间段、区域和同行人生成 DC 活动清单与路线。
- 变现方式：广告、活动/票务联盟、本地商家推广。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: dynamic or official data with weak/unknown supply control; high permutation inflation with weak/unknown canonical supply.
- 关键词条目数：1；总搜索量：14800；最高 CPC：0.37

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| things to do in dc this weekend | 14800 | 40 | 0.37 | cap_P2 | 周末活动规划器，按兴趣、预算、时间段、区域和同行人生成 DC 活动清单与路线。 |

## P2 - venue_event_schedule_lookup

- Canonical key: lookup/single_entity/venue_event_schedule/event_calendar/venue_name
- Badges: Supply=official_or_marketplace_inventory; Freshness=event_bound; Control=weak; Winner=official_source; Permutation=high
- 页面形态：场馆演出日历页，展示即将到来的音乐会、日期、票务入口、座位/停车提示和提醒功能。
- 变现方式：票务联盟、广告、停车或旅行联盟。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: dynamic or official data with weak/unknown supply control; high permutation inflation with weak/unknown canonical supply.
- 关键词条目数：2；总搜索量：30200；最高 CPC：0.33

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| darien lake concerts | 18100 | 40 | 0.33 | cap_P2 | 场馆演出日历页，展示即将到来的音乐会、日期、票务入口、座位/停车提示和提醒功能。 |
| sofi stadium events | 12100 | 32 | 0.25 | cap_P2 | 场馆活动日历页，聚合演出和比赛，支持日期筛选、提醒、交通/停车信息和票务跳转。 |

## P2 - fighter_next_event_lookup

- Canonical key: lookup/single_entity/fighter_next_event/event_status_panel/fighter_name
- Badges: Supply=live_external_data; Freshness=event_bound; Control=weak; Winner=specialized_data_provider; Permutation=medium
- 页面形态：拳手下一场比赛查询页，展示对手、时间、地点、票务入口、倒计时和历史赛程摘要。
- 变现方式：广告、票务联盟、赛事提醒订阅。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: dynamic or official data with weak/unknown supply control.
- 关键词条目数：1；总搜索量：18100；最高 CPC：0

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| claressa shields next fight | 18100 | 29 | 0 | cap_P2 | 拳手下一场比赛查询页，展示对手、时间、地点、票务入口、倒计时和历史赛程摘要。 |

## P2 - artist_setlist_lookup

- Canonical key: lookup/single_entity/artist_setlist/setlist_history_page/artist_alias
- Badges: Supply=subjective_or_ugc; Freshness=event_bound; Control=weak; Winner=community_or_forum; Permutation=high
- 页面形态：艺人别名 setlist 页面，规范化到对应艺人后展示近期/历史曲目、巡演筛选和别名消歧。
- 变现方式：广告、音乐平台联盟、票务联盟。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: high permutation inflation with weak/unknown canonical supply.
- 关键词条目数：1；总搜索量：14800；最高 CPC：0

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| nin setlist | 14800 | 34 | 0 | cap_P2 | 艺人别名 setlist 页面，规范化到对应艺人后展示近期/历史曲目、巡演筛选和别名消歧。 |
