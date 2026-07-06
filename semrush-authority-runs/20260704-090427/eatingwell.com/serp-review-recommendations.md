# SERP 复核推荐词簇

二筛候选来源数：5
推荐词簇数：4
推荐关键词条目数：5

| 优先级 | 词簇数 | 关键词条目数 |
| --- | ---: | ---: |
| P0 | 0 | 0 |
| P1 | 3 | 3 |
| P2 | 1 | 2 |

优先级说明：
- P0：优先复核；供给可控、维护有界、差异化清楚，且不是由排列组合搜索量硬抬上来。
- P1：随后复核；机会成立，但数据供给、自然赢家或执行成本还需要确认。
- P2：长尾、cluster seed 或需数据源确认；不是自动拒绝。

## P1 - 食材差异与替代比例对照

- Canonical key: comparison/entity_pair/ingredient_substitution_or_difference/side_by_side_substitution_table/ingredient_pair
- Badges: Supply=stable_public_data; Freshness=none; Control=strong; Winner=unknown; Permutation=medium
- 页面形态：并列表格展示口味、外观、用途、可替代性和换算建议，并允许扩展到其他食材对比。
- 变现方式：广告、食材替代工具、购物联盟链接
- 为什么值得复核：Priority derived from semantic evidence.
- 关键词条目数：1；总搜索量：12100；最高 CPC：0.02

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| chives vs green onions | 12100 | 39 | 0.02 | none | 并列表格展示口味、外观、用途、可替代性和换算建议，并允许扩展到其他食材对比。 |

## P1 - 食品保质期与变质迹象检查器

- Canonical key: checker/single_entity/food_shelf_life/storage_shelf_life_panel/food_item_storage_state
- Badges: Supply=stable_public_data; Freshness=low; Control=strong; Winner=unknown; Permutation=high
- 页面形态：输入食品、是否开封、储存方式和日期后返回保质期范围、变质迹象和处理建议的检查器。
- 变现方式：广告、厨房管理工具、食品储存清单模板
- 为什么值得复核：Priority derived from semantic evidence.
- 关键词条目数：1；总搜索量：14800；最高 CPC：0.01

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| does apple cider vinegar go bad | 14800 | 31 | 0.01 | none | 输入食品、是否开封、储存方式和日期后返回保质期范围、变质迹象和处理建议的检查器。 |

## P1 - 饮品保质期与变质迹象检查器

- Canonical key: checker/single_entity/beverage_shelf_life/storage_shelf_life_panel/beverage_type_storage_state
- Badges: Supply=stable_public_data; Freshness=low; Control=strong; Winner=unknown; Permutation=high
- 页面形态：按啤酒类型、包装、开封状态和储存条件返回可饮用窗口、风味劣化提示和丢弃判断的检查器。
- 变现方式：广告、饮品储存指南、酒类电商联盟链接
- 为什么值得复核：Priority derived from semantic evidence.
- 关键词条目数：1；总搜索量：12100；最高 CPC：0.01

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| does beer go bad | 12100 | 18 | 0.01 | none | 按啤酒类型、包装、开封状态和储存条件返回可饮用窗口、风味劣化提示和丢弃判断的检查器。 |

## P2 - 食品召回状态查询与提醒

- Canonical key: tracker/single_entity/food_recall/recall_status_table/food_category_or_product
- Badges: Supply=live_external_data; Freshness=live; Control=medium; Winner=official_source; Permutation=medium
- 页面形态：按食品类别、品牌、日期和风险级别筛选的召回查询页，链接到官方召回来源并提供订阅提醒。
- 变现方式：广告、邮件提醒订阅、食品安全工具赞助
- 为什么值得复核：Priority derived from semantic evidence; cap applied: live freshness with high/unknown maintenance burden.
- 关键词条目数：2；总搜索量：45200；最高 CPC：0.72

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| cheese recall | 33100 | 31 | 0.72 | cap_P2 | 按食品类别、品牌、日期和风险级别筛选的召回查询页，链接到官方召回来源并提供订阅提醒。 |
| tomatoes recalled | 12100 | 22 | 0 | cap_P2 | 针对番茄及相关产品的召回状态面板，按地区、品牌、批次和发布日期筛选，并保留官方来源链接。 |
