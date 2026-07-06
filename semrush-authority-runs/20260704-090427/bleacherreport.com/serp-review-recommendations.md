# SERP 复核推荐词簇

二筛候选来源数：4
推荐词簇数：2
推荐关键词条目数：4

| 优先级 | 词簇数 | 关键词条目数 |
| --- | ---: | ---: |
| P0 | 0 | 0 |
| P1 | 1 | 1 |
| P2 | 1 | 3 |

优先级说明：
- P0：优先复核；供给可控、维护有界、差异化清楚，且不是由排列组合搜索量硬抬上来。
- P1：随后复核；机会成立，但数据供给、自然赢家或执行成本还需要确认。
- P2：长尾、cluster seed 或需数据源确认；不是自动拒绝。

## P1 - 教练合同买断金额查询

- Canonical key: lookup/single_entity/coach_contract_buyout/contract_terms_buyout_schedule/coach_team
- Badges: Supply=stable_public_data; Freshness=periodic; Control=medium; Winner=official_source; Permutation=low
- 页面形态：单页合同条款与买断金额查询，展示当前买断估算、关键日期、条款来源和历史变动。
- 变现方式：广告、体育数据订阅、教练合同数据库延展。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: natural winner is strong, but independent differentiation is credible.
- 关键词条目数：1；总搜索量：22200；最高 CPC：0

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| deion sanders colorado buffaloes contract buyout | 22200 | 38 | 0 | cap_P1 | 单页合同条款与买断金额查询，展示当前买断估算、关键日期、条款来源和历史变动。 |

## P2 - WNBA 对阵球员数据查询

- Canonical key: lookup/entity_pair/event_player_stats/sortable_data_page/team_a_vs_team_b
- Badges: Supply=periodic_public_data; Freshness=event_bound; Control=weak; Winner=specialized_data_provider; Permutation=high
- 页面形态：按球队对阵生成的球员数据页，包含可排序 box score、球员基础数据、历史交锋筛选和来源标注。
- 变现方式：广告、体育数据订阅、赛事数据 API 联盟或相关内容内链。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: high permutation inflation with weak/unknown canonical supply.
- 关键词条目数：3；总搜索量：132400；最高 CPC：0

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| indiana fever vs atlanta dream match player stats | 90500 | 29 | 0 | cap_P2 | 可排序的对阵球员统计页，展示球员得分、篮板、助攻等核心 box score，并提供历史对阵切换。 |
| golden state valkyries vs indiana fever match player stats | 27100 | 31 | 0 | cap_P2 | 球队对阵球员数据页，支持球员维度排序、球队汇总、最近比赛切换和数据来源说明。 |
| golden state valkyries vs atlanta dream match player stats | 14800 | 22 | 0 | cap_P2 | 按球队对阵生成的球员数据页，包含可排序 box score、球员基础数据、历史交锋筛选和来源标注。 |
