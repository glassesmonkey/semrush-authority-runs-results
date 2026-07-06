# SERP 复核推荐词簇

二筛候选来源数：10
推荐词簇数：2
推荐关键词条目数：10

| 优先级 | 词簇数 | 关键词条目数 |
| --- | ---: | ---: |
| P0 | 0 | 0 |
| P1 | 1 | 4 |
| P2 | 1 | 6 |

优先级说明：
- P0：优先复核；供给可控、维护有界、差异化清楚，且不是由排列组合搜索量硬抬上来。
- P1：随后复核；机会成立，但数据供给、自然赢家或执行成本还需要确认。
- P2：长尾、cluster seed 或需数据源确认；不是自动拒绝。

## P1 - 国家队对阵历史数据对比

- Canonical key: lookup/entity_pair/team_head_to_head_stats/comparison_stats_page/team_a_vs_team_b
- Badges: Supply=periodic_public_data; Freshness=periodic; Control=medium; Winner=specialized_data_provider; Permutation=high
- 页面形态：可筛选的国家队交锋历史、比分趋势、进球/胜负统计和时间线对比页。
- 变现方式：广告；体育数据工具导流；合规的赛事内容联盟合作。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: natural winner is strong, but independent differentiation is credible.
- 关键词条目数：4；总搜索量：54400；最高 CPC：0

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| brazil national football team vs france national football team stats | 18100 | 34 | 0 | cap_P1 | 可筛选的国家队交锋历史、比分趋势、进球/胜负统计和时间线对比页。 |
| nigeria national football team vs morocco national football team stats | 12100 | 32 | 0 | cap_P1 | 国家队交锋历史、胜平负、进失球、赛事分布和最近比赛趋势的可视化对比页。 |
| panama national football team vs mexico national football team stats | 12100 | 22 | 0 | cap_P1 | 国家队历史交锋统计、比分趋势、赛事类型过滤和近期状态对比页。 |
| senegal national football team vs morocco national football team stats | 12100 | 36 | 0 | cap_P1 | 国家队交锋历史、胜平负、进球趋势、赛事阶段过滤和最近交锋可视化页。 |

## P2 - 球队对阵球员数据表

- Canonical key: lookup/entity_pair/event_player_stats/sortable_data_page/team_a_vs_team_b
- Badges: Supply=live_external_data; Freshness=event_bound; Control=weak; Winner=specialized_data_provider; Permutation=high
- 页面形态：按球员、球队和统计项排序的比赛球员数据页，附历史对阵和单场表现筛选。
- 变现方式：广告；体育数据/API 工具导流；合规联盟合作。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: dynamic or official data with weak/unknown supply control; high permutation inflation with weak/unknown canonical supply.
- 关键词条目数：6；总搜索量：121400；最高 CPC：0

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| colorado rockies vs mets match player stats | 27100 | 34 | 0 | cap_P2 | 可排序的球员 box score、球队分组、关键指标筛选和历史交锋表现页。 |
| detroit pistons vs denver nuggets match player stats | 27100 | 39 | 0 | cap_P2 | 可排序的单场球员统计表，结合球队过滤、关键球员高亮和历史交锋表现对比。 |
| detroit pistons vs dallas mavericks match player stats | 22200 | 39 | 0 | cap_P2 | 按球员、球队、得分、篮板、助攻等字段排序的比赛统计页，并支持历史同队对阵过滤。 |
| st. louis cardinals vs washington nationals match player stats | 18100 | 25 | 0 | cap_P2 | 按球员与统计项排序的 MLB 比赛数据页，支持球队筛选、关键指标排序和历史 matchup 对比。 |
| chicago cubs vs houston astros match player stats | 14800 | 34 | 0 | cap_P2 | 按球员、球队和统计项排序的比赛球员数据页，附历史对阵和单场表现筛选。 |
| los angeles angels vs baltimore orioles match player stats | 12100 | 27 | 0 | cap_P2 | 球员级 box score、球队分组、投打关键指标排序和历史同 matchup 统计页。 |
