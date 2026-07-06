# SERP 复核推荐词簇

二筛候选来源数：21
推荐词簇数：11
推荐关键词条目数：21

| 优先级 | 词簇数 | 关键词条目数 |
| --- | ---: | ---: |
| P0 | 0 | 0 |
| P1 | 11 | 21 |
| P2 | 0 | 0 |

优先级说明：
- P0：优先复核；供给可控、维护有界、差异化清楚，且不是由排列组合搜索量硬抬上来。
- P1：随后复核；机会成立，但数据供给、自然赢家或执行成本还需要确认。
- P2：长尾、cluster seed 或需数据源确认；不是自动拒绝。

## P1 - 鸡胸肉烹饪时间计算器

- Canonical key: calculator/single_entity/chicken_breast_cook_time/time_temperature_calculator/cut_thickness_weight_oven_temp_target_temp
- Badges: Supply=user_input_transform; Freshness=low; Control=medium; Winner=independent_tool; Permutation=medium
- 页面形态：输入厚度、重量、烤箱温度和是否带骨后返回时间区间、目标内部温度、静置时间和温度计检查点。
- 变现方式：广告、温度计/烤盘联盟、餐食计划工具。
- 为什么值得复核：Priority derived from semantic evidence.
- 关键词条目数：2；总搜索量：90000；最高 CPC：0.04

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| how long to bake chicken breast | 49500 | 37 | 0.04 | none | 输入厚度、重量、烤箱温度和是否带骨后返回时间区间、目标内部温度、静置时间和温度计检查点。 |
| how long to cook chicken breast in oven | 40500 | 37 | 0.04 | none | 烤箱鸡胸肉时间计算器，按厚度、重量、温度、是否腌制和目标口感输出时间与安全温度检查。 |

## P1 - 食物安全烹饪温度查询

- Canonical key: lookup/single_entity/food_safe_cook_temperature/temperature_table/food_cut_cooking_method
- Badges: Supply=stable_public_data; Freshness=low; Control=medium; Winner=official_source; Permutation=medium
- 页面形态：按鸡肉部位和烹饪方式查询目标内部温度、静置时间、温度计位置和安全说明。
- 变现方式：广告、温度计/厨房工具联盟、可打印温度表。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: natural winner is strong, but independent differentiation is credible.
- 关键词条目数：1；总搜索量：27100；最高 CPC：0.04

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| chicken cook temp | 27100 | 37 | 0.04 | cap_P1 | 按鸡肉部位和烹饪方式查询目标内部温度、静置时间、温度计位置和安全说明。 |

## P1 - 厨房材料安全检查器

- Canonical key: checker/entity_pair/kitchen_material_safety/safety_rule_checker/appliance_material_food_context
- Badges: Supply=stable_public_data; Freshness=low; Control=medium; Winner=official_source; Permutation=medium
- 页面形态：选择厨具、材料和食物类型后返回可否使用、放置限制、替代材料和清洁/安全提醒。
- 变现方式：广告、厨房耗材联盟、空气炸锅配件联盟。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: natural winner is strong, but independent differentiation is credible.
- 关键词条目数：2；总搜索量：29600；最高 CPC：0.03

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| can you put aluminum foil in an air fryer | 14800 | 24 | 0.03 | cap_P1 | 选择厨具、材料和食物类型后返回可否使用、放置限制、替代材料和清洁/安全提醒。 |
| can you put foil in an air fryer | 14800 | 34 | 0.03 | cap_P1 | 空气炸锅材料检查器，按材料、篮型、食物酸性和摆放方式给出可用/禁用/替代建议。 |

## P1 - 配料替代比例查询

- Canonical key: converter/single_entity/ingredient_substitution/substitution_ratio_table/ingredient_amount_recipe_context
- Badges: Supply=stable_public_data; Freshness=low; Control=medium; Winner=independent_tool; Permutation=medium
- 页面形态：输入原料、用量和食谱语境后返回替代比例、酸碱/发酵注意事项和失败风险提示。
- 变现方式：广告、食材联盟、可打印替代表和烘焙工具包。
- 为什么值得复核：Priority derived from semantic evidence.
- 关键词条目数：7；总搜索量：119000；最高 CPC：0.02

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| soy sauce substitute | 18100 | 32 | 0.02 | none | 酱油替代换算器，按菜系、钠限制、无麸质/无大豆需求和用量返回替代物及比例。 |
| substitute for baking powder | 14800 | 25 | 0.02 | none | 输入所需烘焙粉用量和食谱类型后返回小苏打/酸源组合、液体调整和失败风险提示。 |
| tomato paste substitute | 14800 | 29 | 0.02 | none | 番茄膏替代换算器，按用量、菜式、浓稠度和可用番茄制品返回替代比例与减水建议。 |
| evaporated milk substitute | 12100 | 29 | 0.02 | none | 淡奶替代换算器，按菜谱类型、用量、乳制品限制和甜咸用途返回替代物及比例。 |
| baking soda substitute | 22200 | 30 | 0.01 | none | 输入原料、用量和食谱语境后返回替代比例、酸碱/发酵注意事项和失败风险提示。 |
| mirin substitute | 22200 | 28 | 0.01 | none | 味醂替代换算器，按菜系、酒精限制、甜咸用途和用量返回替代组合及比例。 |
| corn starch substitute | 14800 | 30 | 0.01 | none | 玉米淀粉替代换算器，按用途、用量和饮食限制返回替代物、比例和口感变化。 |

## P1 - 剩菜复热方法选择器

- Canonical key: workflow/single_entity/food_reheating_method/method_time_selector/food_appliance_portion_size_texture_goal
- Badges: Supply=user_input_transform; Freshness=low; Control=medium; Winner=unknown; Permutation=medium
- 页面形态：选择空气炸锅、烤箱、平底锅或微波炉后返回时间、温度、脆皮恢复技巧和安全检查点。
- 变现方式：广告、厨房设备联盟、剩菜复热指南包。
- 为什么值得复核：Priority derived from semantic evidence.
- 关键词条目数：1；总搜索量：90500；最高 CPC：0.02

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| how to reheat fried chicken | 90500 | 35 | 0.02 | none | 选择空气炸锅、烤箱、平底锅或微波炉后返回时间、温度、脆皮恢复技巧和安全检查点。 |

## P1 - 酵母活性检测流程

- Canonical key: checker/single_entity/yeast_viability/diagnostic_flow/yeast_type_water_temp_time_visual_result
- Badges: Supply=user_input_transform; Freshness=low; Control=medium; Winner=independent_tool; Permutation=low
- 页面形态：按酵母类型、水温、等待时间和泡沫状态引导判断酵母是否可用，并给出下一步补救。
- 变现方式：广告、烘焙工具/酵母联盟、烘焙课程。
- 为什么值得复核：Priority derived from semantic evidence.
- 关键词条目数：1；总搜索量：90500；最高 CPC：0.02

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| how to proof yeast | 90500 | 27 | 0.02 | none | 按酵母类型、水温、等待时间和泡沫状态引导判断酵母是否可用，并给出下一步补救。 |

## P1 - 家居清洁消毒流程检查器

- Canonical key: checker/single_entity/household_sanitization_method/method_safety_checklist/item_method_material_condition
- Badges: Supply=stable_public_data; Freshness=low; Control=medium; Winner=official_source; Permutation=medium
- 页面形态：按海绵类型、消毒方式和使用状态给出可行步骤、时间、禁忌和何时直接丢弃。
- 变现方式：广告、清洁用品联盟、家庭清洁清单。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: natural winner is strong, but independent differentiation is credible.
- 关键词条目数：1；总搜索量：60500；最高 CPC：0.02

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| how to sanitize sponges | 60500 | 37 | 0.02 | cap_P1 | 按海绵类型、消毒方式和使用状态给出可行步骤、时间、禁忌和何时直接丢弃。 |

## P1 - 烹饪油结构化对比

- Canonical key: comparison/entity_pair/ingredient_cooking_properties/structured_comparison_table/ingredient_a_ingredient_b_cooking_use
- Badges: Supply=stable_public_data; Freshness=low; Control=medium; Winner=unknown; Permutation=medium
- 页面形态：按烟点、风味、中性程度、烘焙替代、煎炸适配和过敏/饮食标签展示可过滤对比表。
- 变现方式：广告、食材联盟、厨房基础课或替代指南。
- 为什么值得复核：Priority derived from semantic evidence.
- 关键词条目数：2；总搜索量：26900；最高 CPC：0.02

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| canola oil vs vegetable oil | 14800 | 32 | 0.02 | none | 按烟点、风味、中性程度、烘焙替代、煎炸适配和过敏/饮食标签展示可过滤对比表。 |
| canola vs vegetable oil | 12100 | 26 | 0.02 | none | 烹饪油对比器，按用途输出能否互换、口味影响、烟点区间和最佳使用场景。 |

## P1 - 食品保质与变质检查器

- Canonical key: checker/single_entity/food_spoilage_storage/freshness_decision_tree/food_storage_state_date_sensory_signs
- Badges: Supply=stable_public_data; Freshness=low; Control=medium; Winner=official_source; Permutation=medium
- 页面形态：输入开封状态、储存方式、日期和气味/外观迹象后给出保留、丢弃或谨慎处理建议。
- 变现方式：广告、厨房收纳/标签工具联盟、家庭食品安全清单。
- 为什么值得复核：Priority derived from semantic evidence.
- 关键词条目数：2；总搜索量：24200；最高 CPC：0.02

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| does peanut butter go bad | 12100 | 34 | 0.02 | none | 输入开封状态、储存方式、日期和气味/外观迹象后给出保留、丢弃或谨慎处理建议。 |
| how to tell if chicken is bad | 12100 | 36 | 0.02 | cap_P1 | 输入购买/开封日期、冷藏/冷冻状态、气味、颜色、质地和包装情况后给出丢弃/谨慎/可继续处理建议。 |

## P1 - 乳制品用途与替代对比

- Canonical key: comparison/entity_pair/ingredient_cooking_properties/structured_comparison_table/ingredient_a_ingredient_b_recipe_context
- Badges: Supply=stable_public_data; Freshness=low; Control=medium; Winner=unknown; Permutation=medium
- 页面形态：按脂肪含量、打发稳定性、烘焙/酱汁/咖啡用途和可替代性输出结构化比较。
- 变现方式：广告、食材联盟、烘焙指南。
- 为什么值得复核：Priority derived from semantic evidence.
- 关键词条目数：1；总搜索量：27100；最高 CPC：0.01

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| heavy cream vs heavy whipping cream | 27100 | 32 | 0.01 | none | 按脂肪含量、打发稳定性、烘焙/酱汁/咖啡用途和可替代性输出结构化比较。 |

## P1 - 食物节日日期查询

- Canonical key: lookup/entity_date/food_holiday_calendar/date_table/holiday_year
- Badges: Supply=periodic_public_data; Freshness=periodic; Control=strong; Winner=unknown; Permutation=high
- 页面形态：按节日名和年份查询日期、星期、历史日期和相关提醒，可扩展为食物节日日历。
- 变现方式：广告、日历订阅、餐饮促销模板。
- 为什么值得复核：Priority derived from semantic evidence.
- 关键词条目数：1；总搜索量：18100；最高 CPC：0

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| national taco day 2025 | 18100 | 35 | 0 | none | 按节日名和年份查询日期、星期、历史日期和相关提醒，可扩展为食物节日日历。 |
