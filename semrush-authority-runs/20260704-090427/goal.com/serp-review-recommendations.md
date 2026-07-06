# SERP 复核推荐词簇

二筛候选来源数：7
推荐词簇数：3
推荐关键词条目数：7

| 优先级 | 词簇数 | 关键词条目数 |
| --- | ---: | ---: |
| P0 | 0 | 0 |
| P1 | 2 | 6 |
| P2 | 1 | 1 |

优先级说明：
- P0：优先复核；供给可控、维护有界、差异化清楚，且不是由排列组合搜索量硬抬上来。
- P1：随后复核；机会成立，但数据供给、自然赢家或执行成本还需要确认。
- P2：长尾、cluster seed 或需数据源确认；不是自动拒绝。

## P1 - football_team_standings_lookup

- Canonical key: lookup/single_entity/football_team_standings/standings_table/team_name_standings
- Badges: Supply=periodic_public_data; Freshness=periodic; Control=medium; Winner=specialized_data_provider; Permutation=high
- 页面形态：球队维度的当前积分榜页，包含赛事切换、排名、场次、净胜球和近期变化。
- 变现方式：广告，体育数据联盟，赛事页内推荐。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: natural winner is strong, but independent differentiation is credible.
- 关键词条目数：5；总搜索量：174500；最高 CPC：0

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| manchester united standings | 110000 | 40 | 0 | cap_P1 | 俱乐部 standings 数据页，支持赛事切换、排名趋势、近期赛果和关键表格指标。 |
| cruz azul standings | 22200 | 36 | 0 | cap_P1 | 俱乐部当前积分榜页，支持赛事过滤、排名变化、近期赛果和关键指标表。 |
| milan standings | 18100 | 40 | 0 | cap_P1 | 球队 standings 页，先消解球队实体，再展示赛事维度积分榜、排名变化和更新时间。 |
| colombia national football team standings | 12100 | 32 | 0 | cap_P1 | 球队维度的当前积分榜页，包含赛事切换、排名、场次、净胜球和近期变化。 |
| guatemala national football team standings | 12100 | 40 | 0 | cap_P1 | 国家队积分榜页，按赛事展示排名、场次、积分、净胜球和更新时间。 |

## P1 - football_team_standings_lookup

- Canonical key: lookup/single_entity/football_team_standings/standings_table/team_name_posiciones
- Badges: Supply=periodic_public_data; Freshness=periodic; Control=medium; Winner=specialized_data_provider; Permutation=high
- 页面形态：西语国家队积分榜页，按赛事展示排名、积分、场次、净胜球和最近更新时间。
- 变现方式：广告，体育数据联盟，西语赛事页导流。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: natural winner is strong, but independent differentiation is credible.
- 关键词条目数：1；总搜索量：22200；最高 CPC：0

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| posiciones de selección de fútbol de guatemala | 22200 | 30 | 0 | cap_P1 | 西语国家队积分榜页，按赛事展示排名、积分、场次、净胜球和最近更新时间。 |

## P2 - football_match_lineups_lookup

- Canonical key: lookup/entity_pair/football_match_lineups/formation_lineup_panel/team_a_contra_team_b
- Badges: Supply=live_external_data; Freshness=event_bound; Control=weak; Winner=official_source; Permutation=high
- 页面形态：按对阵展示首发、替补、阵型和更新时间的可视化阵容页。
- 变现方式：广告，体育数据联盟或赛前工具导流。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: dynamic or official data with weak/unknown supply control; high permutation inflation with weak/unknown canonical supply.
- 关键词条目数：1；总搜索量：27100；最高 CPC：0

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| alineaciones de real valladolid contra futbol club barcelona | 27100 | 24 | 0 | cap_P2 | 按对阵展示首发、替补、阵型和更新时间的可视化阵容页。 |
