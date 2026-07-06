# SERP 复核推荐词簇

二筛候选来源数：9
推荐词簇数：4
推荐关键词条目数：9

| 优先级 | 词簇数 | 关键词条目数 |
| --- | ---: | ---: |
| P0 | 0 | 0 |
| P1 | 3 | 8 |
| P2 | 1 | 1 |

优先级说明：
- P0：优先复核；供给可控、维护有界、差异化清楚，且不是由排列组合搜索量硬抬上来。
- P1：随后复核；机会成立，但数据供给、自然赢家或执行成本还需要确认。
- P2：长尾、cluster seed 或需数据源确认；不是自动拒绝。

## P1 - 食物热量查询

- Canonical key: lookup/single_entity/food_nutrition/serving_size_calculator/food_serving_size
- Badges: Supply=stable_public_data; Freshness=low; Control=medium; Winner=specialized_data_provider; Permutation=high
- 页面形态：食物热量查询页，支持克数、杯、片等份量换算，并显示基础营养数据来源。
- 变现方式：广告、饮食记录工具导流、健康食品联盟
- 为什么值得复核：Priority derived from semantic evidence; cap applied: natural winner is strong, but independent differentiation is credible.
- 关键词条目数：1；总搜索量：14800；最高 CPC：0.45

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| cucumber calories | 14800 | 36 | 0.45 | cap_P1 | 食物热量查询页，支持克数、杯、片等份量换算，并显示基础营养数据来源。 |

## P1 - 宠物食物安全查询

- Canonical key: lookup/entity_pair/pet_food_safety/safety_status_panel/species_food
- Badges: Supply=stable_public_data; Freshness=low; Control=medium; Winner=specialized_data_provider; Permutation=high
- 页面形态：按宠物种类和食物输出可食用状态、主要风险、准备方式和何时咨询兽医的结构化查询页。
- 变现方式：广告、宠物食品/用品联盟、兽医远程咨询线索
- 为什么值得复核：Priority derived from semantic evidence; cap applied: natural winner is strong, but independent differentiation is credible.
- 关键词条目数：4；总搜索量：106500；最高 CPC：0.15

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| can dogs eat eggs | 33100 | 35 | 0.15 | cap_P1 | 按宠物种类和食物输出可食用状态、主要风险、准备方式和何时咨询兽医的结构化查询页。 |
| can dogs have eggs | 22200 | 37 | 0.15 | cap_P1 | 宠物食物安全查询页，展示可食用结论、注意事项、准备方式和危险信号。 |
| can dogs eat peanuts | 33100 | 38 | 0.1 | cap_P1 | 食物安全状态卡，区分原味/调味/含木糖醇等情形，并给出风险提示和来源链接。 |
| can dogs have peanuts | 18100 | 33 | 0.1 | cap_P1 | 按犬类和花生形态输出安全状态、禁忌添加剂、适量提示和紧急风险说明的查询卡。 |

## P1 - 食材替代查询

- Canonical key: lookup/single_entity/ingredient_substitution/substitution_ratio_table/ingredient_use_case
- Badges: Supply=stable_public_data; Freshness=none; Control=strong; Winner=independent_tool; Permutation=medium
- 页面形态：输入原食材和用途，输出替代品、比例、口感差异和适用/不适用场景的查询表。
- 变现方式：广告、厨具/食材联盟、食谱模板
- 为什么值得复核：Priority derived from semantic evidence.
- 关键词条目数：3；总搜索量：49100；最高 CPC：0.01

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| cornstarch substitute | 22200 | 39 | 0.01 | none | 食材替代查询器，按增稠、烘焙、炸物等用途返回替代品和换算比例。 |
| corn starch substitute | 14800 | 30 | 0.01 | none | 输入原食材和用途，输出替代品、比例、口感差异和适用/不适用场景的查询表。 |
| substitute for cornstarch | 12100 | 37 | 0.01 | none | 按用途返回玉米淀粉替代品、换算比例、质地影响和失败风险的交互式表格。 |

## P2 - 激光脱毛费用估算

- Canonical key: calculator/many_permutations/cosmetic_service_cost/cost_estimator/service_body_area_location
- Badges: Supply=periodic_public_data; Freshness=periodic; Control=weak; Winner=marketplace; Permutation=high
- 页面形态：激光脱毛费用估算器，按部位、疗程次数、地区和诊所类型给出价格区间与变量说明。
- 变现方式：本地医美线索、广告、诊所联盟
- 为什么值得复核：Priority derived from semantic evidence; cap applied: high permutation inflation with weak/unknown canonical supply.
- 关键词条目数：1；总搜索量：22200；最高 CPC：5.3

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| cost laser hair | 22200 | 36 | 5.3 | cap_P2 | 激光脱毛费用估算器，按部位、疗程次数、地区和诊所类型给出价格区间与变量说明。 |
