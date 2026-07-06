# SERP 复核推荐词簇

二筛候选来源数：31
推荐词簇数：25
推荐关键词条目数：31

| 优先级 | 词簇数 | 关键词条目数 |
| --- | ---: | ---: |
| P0 | 0 | 0 |
| P1 | 20 | 25 |
| P2 | 5 | 6 |

优先级说明：
- P0：优先复核；供给可控、维护有界、差异化清楚，且不是由排列组合搜索量硬抬上来。
- P1：随后复核；机会成立，但数据供给、自然赢家或执行成本还需要确认。
- P2：长尾、cluster seed 或需数据源确认；不是自动拒绝。

## P1 - 公共厕所查找器

- Canonical key: lookup/entity_location/public_toilet_locator/amenity_map_with_accessibility_filters/user_location
- Badges: Supply=stable_public_data; Freshness=periodic; Control=medium; Winner=independent_tool; Permutation=high
- 页面形态：按距离、开放时间、无障碍、免费、婴儿台和最近确认时间过滤的公共厕所地图。
- 变现方式：广告/城市服务赞助
- 为什么值得复核：Priority derived from semantic evidence; cap applied: maintenance burden is medium and supply control is not strong.
- 关键词条目数：1；总搜索量：22200；最高 CPC：28.96

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| near me public toilet | 22200 | 40 | 28.96 | cap_P1 | 按距离、开放时间、无障碍、免费、婴儿台和最近确认时间过滤的公共厕所地图。 |

## P1 - 现金返还地点查找器

- Canonical key: lookup/entity_location/cashback_location_policy/policy_map_and_table/user_location_and_cash_amount
- Badges: Supply=periodic_public_data; Freshness=periodic; Control=medium; Winner=specialized_data_provider; Permutation=high
- 页面形态：按商户、最低消费、返现金额上限、手续费和距离聚合的现金返还地点表。
- 变现方式：广告/金融服务联盟
- 为什么值得复核：Priority derived from semantic evidence; cap applied: natural winner is strong, but independent differentiation is credible.
- 关键词条目数：1；总搜索量：12100；最高 CPC：7.41

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| cash back near me | 12100 | 32 | 7.41 | cap_P1 | 按商户、最低消费、返现金额上限、手续费和距离聚合的现金返还地点表。 |

## P1 - 硬币兑换机查找器

- Canonical key: lookup/entity_location/coin_machine_locator/amenity_map_with_fees/user_location
- Badges: Supply=periodic_public_data; Freshness=periodic; Control=medium; Winner=specialized_data_provider; Permutation=high
- 页面形态：显示硬币机位置、手续费、营业时间、银行/超市类型和最近确认时间的地图。
- 变现方式：广告/本地线索
- 为什么值得复核：Priority derived from semantic evidence; cap applied: natural winner is strong, but independent differentiation is credible.
- 关键词条目数：1；总搜索量：33100；最高 CPC：7.14

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| coin machine near me | 33100 | 29 | 7.14 | cap_P1 | 显示硬币机位置、手续费、营业时间、银行/超市类型和最近确认时间的地图。 |

## P1 - 公共淋浴设施查找器

- Canonical key: lookup/entity_location/public_shower_locator/amenity_map_with_access_filters/user_location
- Badges: Supply=periodic_public_data; Freshness=periodic; Control=medium; Winner=independent_tool; Permutation=high
- 页面形态：按距离、公共/健身房/营地/卡车站、费用、营业时间、无障碍和最近确认时间过滤的淋浴地图。
- 变现方式：广告/旅行服务联盟
- 为什么值得复核：Priority derived from semantic evidence; cap applied: maintenance burden is medium and supply control is not strong.
- 关键词条目数：2；总搜索量：32900；最高 CPC：4.34

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| showers close to me | 18100 | 20 | 4.34 | cap_P1 | 按距离、公共/健身房/营地/卡车站、费用、营业时间、无障碍和最近确认时间过滤的淋浴地图。 |
| showers near me | 14800 | 25 | 4.34 | cap_P1 | 附近淋浴设施地图，支持按免费、24 小时、公共访问、停车和最近确认时间过滤。 |

## P1 - 洗衣机故障诊断流程

- Canonical key: workflow/single_entity/washing_machine_troubleshooting/diagnostic_decision_tree/symptom_brand_error_code
- Badges: Supply=user_input_transform; Freshness=low; Control=medium; Winner=independent_tool; Permutation=medium
- 页面形态：输入症状、品牌、错误代码和是否漏水后输出排查步骤、零件可能性和维修/更换判断。
- 变现方式：广告/零件联盟/维修线索
- 为什么值得复核：Priority derived from semantic evidence.
- 关键词条目数：1；总搜索量：12100；最高 CPC：3.88

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| fix laundry machine | 12100 | 40 | 3.88 | none | 输入症状、品牌、错误代码和是否漏水后输出排查步骤、零件可能性和维修/更换判断。 |

## P1 - 汽车空调故障诊断流程

- Canonical key: workflow/single_entity/auto_ac_troubleshooting/diagnostic_decision_tree/symptoms_vehicle_context
- Badges: Supply=user_input_transform; Freshness=low; Control=medium; Winner=independent_tool; Permutation=medium
- 页面形态：根据症状、车型、出风温度、压缩机状态和噪音给出排查步骤与何时找技师的诊断工具。
- 变现方式：广告/汽车维修线索/工具联盟
- 为什么值得复核：Priority derived from semantic evidence.
- 关键词条目数：1；总搜索量：12100；最高 CPC：2.94

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| fix auto ac | 12100 | 35 | 2.94 | none | 根据症状、车型、出风温度、压缩机状态和噪音给出排查步骤与何时找技师的诊断工具。 |

## P1 - 运动场地查找器

- Canonical key: lookup/entity_location/sports_court_locator/facility_map_with_filters/sport_and_user_location
- Badges: Supply=stable_public_data; Freshness=periodic; Control=medium; Winner=specialized_data_provider; Permutation=high
- 页面形态：按运动类型、室内/室外、预约要求、灯光、收费和开放时间过滤的球场地图。
- 变现方式：广告/预订线索/会员订阅
- 为什么值得复核：Priority derived from semantic evidence; cap applied: natural winner is strong, but independent differentiation is credible.
- 关键词条目数：2；总搜索量：32900；最高 CPC：2.89

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| basketball court near me | 18100 | 26 | 2.89 | cap_P1 | 显示室内/室外、半场/全场、灯光、开放时间、拥挤度和免费状态的篮球场地图。 |
| badminton court near me | 14800 | 39 | 1.33 | cap_P1 | 按运动类型、室内/室外、预约要求、灯光、收费和开放时间过滤的球场地图。 |

## P1 - 无乙醇汽油站查找器

- Canonical key: lookup/entity_location/ethanol_free_gas_station_locator/fuel_filter_map/fuel_type_and_user_location
- Badges: Supply=periodic_public_data; Freshness=periodic; Control=medium; Winner=specialized_data_provider; Permutation=high
- 页面形态：展示无乙醇汽油站、辛烷值、品牌、距离、营业时间和确认日期的地图。
- 变现方式：广告/汽车用品联盟
- 为什么值得复核：Priority derived from semantic evidence; cap applied: natural winner is strong, but independent differentiation is credible.
- 关键词条目数：3；总搜索量：46400；最高 CPC：2.45

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| ethanol-free gasoline close to me | 12100 | 33 | 2.45 | cap_P1 | 展示无乙醇汽油站、辛烷值、品牌、距离、营业时间和确认日期的地图。 |
| non ethanol gas near me | 22200 | 30 | 1.87 | cap_P1 | 按无乙醇、辛烷值、品牌、距离、营业时间和最近确认时间过滤的加油站地图。 |
| non-ethanol gas close to me | 12100 | 29 | 1.87 | cap_P1 | 显示附近无乙醇汽油站、辛烷值、品牌、营业时间和确认日期的地图。 |

## P1 - 跑道查找器

- Canonical key: lookup/entity_location/running_track_locator/facility_map_with_filters/user_location
- Badges: Supply=stable_public_data; Freshness=periodic; Control=medium; Winner=specialized_data_provider; Permutation=high
- 页面形态：按开放公众、距离、400 米标准、材质、灯光、免费和开放时间过滤的跑道地图。
- 变现方式：广告/运动用品联盟
- 为什么值得复核：Priority derived from semantic evidence; cap applied: natural winner is strong, but independent differentiation is credible.
- 关键词条目数：1；总搜索量：12100；最高 CPC：2.33

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| running track near me | 12100 | 39 | 2.33 | cap_P1 | 按开放公众、距离、400 米标准、材质、灯光、免费和开放时间过滤的跑道地图。 |

## P1 - 室内篮球场查找器

- Canonical key: lookup/entity_location/indoor_basketball_court_locator/facility_map_with_filters/user_location
- Badges: Supply=stable_public_data; Freshness=periodic; Control=medium; Winner=specialized_data_provider; Permutation=high
- 页面形态：按室内、开放时间、预约、收费、地板类型、灯光和距离过滤的篮球场地图。
- 变现方式：广告/场馆预订线索
- 为什么值得复核：Priority derived from semantic evidence; cap applied: natural winner is strong, but independent differentiation is credible.
- 关键词条目数：1；总搜索量：27100；最高 CPC：1.89

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| indoor basketball courts near me | 27100 | 22 | 1.89 | cap_P1 | 按室内、开放时间、预约、收费、地板类型、灯光和距离过滤的篮球场地图。 |

## P1 - 健身房会员价格比较器

- Canonical key: comparison/many_permutations/gym_membership_pricing/sortable_price_comparison_table/budget_location_and_amenities
- Badges: Supply=periodic_public_data; Freshness=periodic; Control=medium; Winner=specialized_data_provider; Permutation=medium
- 页面形态：按城市、预算、设施、月费、年费和取消条款筛选的健身房会员价格比较表。
- 变现方式：联盟/广告/潜在客户转化
- 为什么值得复核：Priority derived from semantic evidence; cap applied: natural winner is strong, but independent differentiation is credible.
- 关键词条目数：1；总搜索量：18100；最高 CPC：1.79

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| affordable gym memberships | 18100 | 24 | 1.79 | cap_P1 | 按城市、预算、设施、月费、年费和取消条款筛选的健身房会员价格比较表。 |

## P1 - 健身房价格比较器

- Canonical key: comparison/many_permutations/gym_membership_pricing/sortable_price_comparison_table/location_budget_amenities
- Badges: Supply=periodic_public_data; Freshness=periodic; Control=medium; Winner=specialized_data_provider; Permutation=medium
- 页面形态：汇总月费、注册费、年费、合约期、试用和设施的健身房价格比较器。
- 变现方式：联盟/广告/本地线索
- 为什么值得复核：Priority derived from semantic evidence; cap applied: natural winner is strong, but independent differentiation is credible.
- 关键词条目数：1；总搜索量：22200；最高 CPC：1.78

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| cheapest gym prices | 22200 | 20 | 1.78 | cap_P1 | 汇总月费、注册费、年费、合约期、试用和设施的健身房价格比较器。 |

## P1 - 附近自然水域地图

- Canonical key: lookup/entity_location/nearby_river_locator/geo_map_with_access_filters/user_location_activity_optional
- Badges: Supply=stable_public_data; Freshness=low; Control=strong; Winner=independent_tool; Permutation=high
- 页面形态：基于地理数据展示附近河流、入口点、步道、停车和活动适配的地图。
- 变现方式：广告/户外用品联盟
- 为什么值得复核：Priority derived from semantic evidence.
- 关键词条目数：1；总搜索量：18100；最高 CPC：1.75

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| rivers near me | 18100 | 17 | 1.75 | none | 基于地理数据展示附近河流、入口点、步道、停车和活动适配的地图。 |

## P1 - 免费轮胎充气点地图

- Canonical key: lookup/entity_location/free_tire_air_station_locator/amenity_map_with_filters/user_location
- Badges: Supply=periodic_public_data; Freshness=periodic; Control=medium; Winner=specialized_data_provider; Permutation=high
- 页面形态：按免费/付费、24 小时、品牌、距离、用户确认时间筛选的轮胎充气地图。
- 变现方式：广告/汽车服务联盟
- 为什么值得复核：Priority derived from semantic evidence; cap applied: natural winner is strong, but independent differentiation is credible.
- 关键词条目数：1；总搜索量：22200；最高 CPC：1.57

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| free air for tires near me | 22200 | 35 | 1.57 | cap_P1 | 按免费/付费、24 小时、品牌、距离、用户确认时间筛选的轮胎充气地图。 |

## P1 - 轮胎充气点地图

- Canonical key: lookup/entity_location/tire_air_station_locator/amenity_map_with_filters/user_location
- Badges: Supply=periodic_public_data; Freshness=periodic; Control=medium; Winner=specialized_data_provider; Permutation=high
- 页面形态：可按距离、免费、24 小时、加油站品牌和最近更新时间筛选的轮胎充气点地图。
- 变现方式：广告/本地商户线索
- 为什么值得复核：Priority derived from semantic evidence; cap applied: natural winner is strong, but independent differentiation is credible.
- 关键词条目数：1；总搜索量：18100；最高 CPC：1.23

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| air for tires close to me | 18100 | 32 | 1.23 | cap_P1 | 可按距离、免费、24 小时、加油站品牌和最近更新时间筛选的轮胎充气点地图。 |

## P1 - 足球场查找器

- Canonical key: lookup/entity_location/soccer_field_locator/facility_map_with_filters/user_location
- Badges: Supply=stable_public_data; Freshness=periodic; Control=medium; Winner=specialized_data_provider; Permutation=high
- 页面形态：按草地/人造草、灯光、可预订、公众开放、尺寸和距离过滤的足球场地图。
- 变现方式：广告/场地预订线索
- 为什么值得复核：Priority derived from semantic evidence; cap applied: natural winner is strong, but independent differentiation is credible.
- 关键词条目数：2；总搜索量：30200；最高 CPC：1.04

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| soccer fields near me | 18100 | 17 | 1.04 | cap_P1 | 显示附近足球场、场地尺寸、草皮、灯光、开放时间、预约方式和费用的地图。 |
| soccer field close to me | 12100 | 32 | 1.04 | cap_P1 | 按草地/人造草、灯光、可预订、公众开放、尺寸和距离过滤的足球场地图。 |

## P1 - 快餐价格比较器

- Canonical key: comparison/many_permutations/fast_food_menu_prices/sortable_price_index/chain_item_location_optional
- Badges: Supply=periodic_public_data; Freshness=periodic; Control=medium; Winner=specialized_data_provider; Permutation=high
- 页面形态：按连锁品牌、餐品类型、卡路里、地区和单价排序的快餐省钱比较器。
- 变现方式：广告/优惠券联盟
- 为什么值得复核：Priority derived from semantic evidence; cap applied: natural winner is strong, but independent differentiation is credible.
- 关键词条目数：1；总搜索量：12100；最高 CPC：1.01

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| cheapest fast food | 12100 | 36 | 1.01 | cap_P1 | 按连锁品牌、餐品类型、卡路里、地区和单价排序的快餐省钱比较器。 |

## P1 - 替代燃料站查找器

- Canonical key: lookup/entity_location/alternative_fuel_station_locator/fuel_filter_map/fuel_type_and_user_location
- Badges: Supply=periodic_public_data; Freshness=periodic; Control=medium; Winner=specialized_data_provider; Permutation=high
- 页面形态：按燃料类型、距离、品牌、营业时间和最近确认时间过滤的 E85 加油站地图。
- 变现方式：广告/汽车服务联盟
- 为什么值得复核：Priority derived from semantic evidence; cap applied: natural winner is strong, but independent differentiation is credible.
- 关键词条目数：1；总搜索量：14800；最高 CPC：0.54

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| e85 gas close to me | 14800 | 33 | 0.54 | cap_P1 | 按燃料类型、距离、品牌、营业时间和最近确认时间过滤的 E85 加油站地图。 |

## P1 - 景观自驾路线规划器

- Canonical key: planner/entity_location/scenic_drive_routes/route_map_with_filters/user_location_duration_preferences
- Badges: Supply=stable_public_data; Freshness=low; Control=medium; Winner=independent_tool; Permutation=high
- 页面形态：根据出发地、时长、景观类型、停车点和季节生成的景观自驾路线地图。
- 变现方式：广告/旅行联盟
- 为什么值得复核：Priority derived from semantic evidence.
- 关键词条目数：1；总搜索量：12100；最高 CPC：0.53

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| driving scenery near me | 12100 | 31 | 0.53 | none | 根据出发地、时长、景观类型、停车点和季节生成的景观自驾路线地图。 |

## P1 - 宠物友好海滩查找器

- Canonical key: lookup/entity_location/dog_friendly_beach_rules/rules_map_with_filters/user_location
- Badges: Supply=stable_public_data; Freshness=periodic; Control=medium; Winner=specialized_data_provider; Permutation=high
- 页面形态：按允许犬只、牵引绳规则、季节限制、停车、距离和设施过滤的宠物友好海滩地图。
- 变现方式：广告/宠物用品联盟
- 为什么值得复核：Priority derived from semantic evidence; cap applied: natural winner is strong, but independent differentiation is credible.
- 关键词条目数：1；总搜索量：12100；最高 CPC：0.39

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| dog beach near me | 12100 | 30 | 0.39 | cap_P1 | 按允许犬只、牵引绳规则、季节限制、停车、距离和设施过滤的宠物友好海滩地图。 |

## P2 - 机油更换价格查找器

- Canonical key: lookup/single_entity/oil_change_price_lookup/price_table_and_estimator/brand_vehicle_location_optional
- Badges: Supply=official_or_marketplace_inventory; Freshness=periodic; Control=weak; Winner=official_source; Permutation=medium
- 页面形态：按车型、机油类型、地区、优惠券和竞品门店展示 Valvoline 换油价格范围的估算表。
- 变现方式：汽车服务联盟/广告
- 为什么值得复核：Priority derived from semantic evidence; cap applied: dynamic or official data with weak/unknown supply control.
- 关键词条目数：1；总搜索量：14800；最高 CPC：1.58

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| valvoline oil change prices | 14800 | 31 | 1.58 | cap_P2 | 按车型、机油类型、地区、优惠券和竞品门店展示 Valvoline 换油价格范围的估算表。 |

## P2 - 机场停车比较器

- Canonical key: comparison/single_entity/airport_parking_options/rate_map_and_booking_comparison/airport_dates_vehicle_type
- Badges: Supply=official_or_marketplace_inventory; Freshness=periodic; Control=weak; Winner=marketplace; Permutation=medium
- 页面形态：比较官方与周边停车场价格、接驳、步行时间、车高限制和预约入口的地图表。
- 变现方式：停车预订联盟/广告
- 为什么值得复核：Priority derived from semantic evidence; cap applied: dynamic or official data with weak/unknown supply control.
- 关键词条目数：1；总搜索量：12100；最高 CPC：1.5

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| oakland airport parking | 12100 | 38 | 1.5 | cap_P2 | 比较官方与周边停车场价格、接驳、步行时间、车高限制和预约入口的地图表。 |

## P2 - 客房按摩浴缸酒店查找器

- Canonical key: lookup/many_permutations/hotel_room_jacuzzi_amenity/amenity_filtered_directory/destination_dates_optional
- Badges: Supply=official_or_marketplace_inventory; Freshness=periodic; Control=weak; Winner=marketplace; Permutation=high
- 页面形态：按目的地、日期、房内按摩浴缸、评分、价格和取消政策过滤的酒店目录。
- 变现方式：酒店联盟/广告
- 为什么值得复核：Priority derived from semantic evidence; cap applied: dynamic or official data with weak/unknown supply control; high permutation inflation with weak/unknown canonical supply.
- 关键词条目数：2；总搜索量：32900；最高 CPC：0.69

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| hotels with jacuzzi in room | 18100 | 27 | 0.69 | cap_P2 | 按目的地、房内按摩浴缸、价格、评分和政策筛选的酒店目录页。 |
| hotel with jacuzzi in room | 14800 | 25 | 0.69 | cap_P2 | 按目的地、日期、房内按摩浴缸、评分、价格和取消政策过滤的酒店目录。 |

## P2 - 主题乐园停车规划器

- Canonical key: planner/single_entity/theme_park_parking/rate_map_and_route_planner/visit_date_vehicle_type
- Badges: Supply=official_or_marketplace_inventory; Freshness=periodic; Control=weak; Winner=official_source; Permutation=medium
- 页面形态：整合官方停车场、价格、入口、步行时间、无障碍选项和替代停车的交互式规划页。
- 变现方式：广告/旅行联盟
- 为什么值得复核：Priority derived from semantic evidence; cap applied: dynamic or official data with weak/unknown supply control.
- 关键词条目数：1；总搜索量：12100；最高 CPC：0.65

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| disneyland parking | 12100 | 40 | 0.65 | cap_P2 | 整合官方停车场、价格、入口、步行时间、无障碍选项和替代停车的交互式规划页。 |

## P2 - 附近房内按摩浴缸酒店查找器

- Canonical key: lookup/entity_location/hotel_room_jacuzzi_amenity/amenity_filtered_map/user_location_dates_optional
- Badges: Supply=official_or_marketplace_inventory; Freshness=periodic; Control=weak; Winner=marketplace; Permutation=high
- 页面形态：以当前位置为中心，过滤房内按摩浴缸、可订日期、价格、停车和取消政策的酒店地图。
- 变现方式：酒店联盟/广告
- 为什么值得复核：Priority derived from semantic evidence; cap applied: dynamic or official data with weak/unknown supply control; high permutation inflation with weak/unknown canonical supply.
- 关键词条目数：1；总搜索量：22200；最高 CPC：0.63

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| hotels near me with jacuzzi in room | 22200 | 28 | 0.63 | cap_P2 | 以当前位置为中心，过滤房内按摩浴缸、可订日期、价格、停车和取消政策的酒店地图。 |
