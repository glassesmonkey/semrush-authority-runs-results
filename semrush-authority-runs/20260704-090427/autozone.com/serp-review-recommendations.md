# SERP 复核推荐词簇

二筛候选来源数：40
推荐词簇数：13
推荐关键词条目数：40

| 优先级 | 词簇数 | 关键词条目数 |
| --- | ---: | ---: |
| P0 | 1 | 1 |
| P1 | 12 | 39 |
| P2 | 0 | 0 |

优先级说明：
- P0：优先复核；供给可控、维护有界、差异化清楚，且不是由排列组合搜索量硬抬上来。
- P1：随后复核；机会成立，但数据供给、自然赢家或执行成本还需要确认。
- P2：长尾、cluster seed 或需数据源确认；不是自动拒绝。

## P0 - 汽车部件测试诊断器

- Canonical key: checker/single_entity/alternator_test/diagnostic_flow/symptoms_voltage_readings_vehicle_state
- Badges: Supply=user_input_transform; Freshness=low; Control=strong; Winner=independent_tool; Permutation=low
- 页面形态：发电机测试向导，收集怠速/负载电压、启动表现和电瓶状态，输出是否疑似发电机故障。
- 变现方式：工具/万用表联盟、发电机配件联盟、维修线索、广告。
- 为什么值得复核：P0 allowed by strong supply control, bounded maintenance, clear differentiation, and high non-content advantage.
- 关键词条目数：1；总搜索量：12100；最高 CPC：0.06

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| how to test alternator | 12100 | 36 | 0.06 | none | 发电机测试向导，收集怠速/负载电压、启动表现和电瓶状态，输出是否疑似发电机故障。 |

## P1 - 汽车维修费用估算器

- Canonical key: calculator/single_entity/vehicle_service_cost/cost_estimate/vehicle_make_model_service_zip
- Badges: Supply=periodic_public_data; Freshness=periodic; Control=medium; Winner=specialized_data_provider; Permutation=medium
- 页面形态：输入车型、地区和服务项目后输出电瓶更换总价区间、零件/人工拆分和省钱方案。
- 变现方式：维修线索、配件联盟、广告。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: natural winner is strong, but independent differentiation is credible.
- 关键词条目数：24；总搜索量：467700；最高 CPC：2.34

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| brake pad replacement cost | 22200 | 31 | 2.34 | cap_P1 | 刹车片更换费用计算器，按前后轴、车型、零件档位和地区输出价格区间。 |
| brake fluid change cost | 18100 | 30 | 2.06 | cap_P1 | 刹车油更换费用估算器，输出人工、材料、区间价格和更换周期提醒。 |
| oil change cost | 22200 | 39 | 1.99 | cap_P1 | 机油更换费用计算器，按车型、机油类型、地区和服务方式输出价格区间。 |
| timing chain replacement cost | 14800 | 31 | 1.98 | cap_P1 | 正时链条更换费用估算器，按车型、发动机、地区和是否更换导轨/张紧器输出价格区间。 |
| how much is an oil change | 27100 | 31 | 1.91 | cap_P1 | 机油更换费用估算器，按车型、机油类型、地区和 DIY/门店选项输出价格。 |
| cost of vehicle tune up | 12100 | 33 | 1.9 | cap_P1 | 车辆 tune-up 费用规划器，按里程、车型和已更换项目生成服务清单与价格区间。 |
| spark plug replacement cost | 12100 | 30 | 1.61 | cap_P1 | 火花塞更换费用估算器，按车型、缸数、火花塞类型和地区输出费用区间。 |
| cost to replace cam belt | 22200 | 40 | 1.47 | cap_P1 | 凸轮/正时皮带更换费用估算器，含里程周期、水泵套件和人工区间。 |
| timing belt replacement cost | 22200 | 32 | 1.47 | cap_P1 | 正时皮带更换费用估算器，含里程周期、水泵套件、人工和地区差异。 |
| car battery replacement cost | 90500 | 29 | 1.33 | cap_P1 | 电瓶更换费用估算器，输出电瓶规格、零件价、安装费、保修和替代方案。 |
| battery change car cost | 12100 | 28 | 1.33 | cap_P1 | 输入车型、地区和服务项目后输出电瓶更换总价区间、零件/人工拆分和省钱方案。 |
| car belt replacement cost | 18100 | 37 | 1.23 | cap_P1 | 车辆皮带更换费用计算器，区分蛇形皮带、正时皮带和附属件，输出成本区间。 |
| head gasket price to repair | 18100 | 32 | 1.22 | cap_P1 | 缸垫维修费用估算器，按症状、车型、地区和是否需机加工输出价格区间。 |
| head gasket repair cost | 12100 | 32 | 1.22 | cap_P1 | 缸垫维修成本计算器，输出轻重程度、人工、零件和替代方案的价格区间。 |
| head gasket replacement cost | 12100 | 40 | 1.05 | cap_P1 | 缸垫更换费用估算器，按车型、发动机、地区和附加维修项输出总价区间。 |
| cost to change catalytic converter | 14800 | 39 | 0.97 | cap_P1 | 催化转换器更换费用估算器，按车型、州/地区合规要求、零件类型和工时报价。 |
| changing engine mounts cost | 12100 | 27 | 0.96 | cap_P1 | 发动机机脚更换费用估算器，输入车型和症状后输出零件、人工与是否需要进一步诊断。 |
| change o2 sensor cost | 14800 | 30 | 0.91 | cap_P1 | 氧传感器更换费用估算器，按车型、传感器位置和故障码输出零件/人工区间。 |
| cv axle change cost | 14800 | 24 | 0.78 | cap_P1 | CV 半轴更换费用计算器，区分左右侧、驱动形式、零件档位和人工区间。 |
| cv axle replacement cost | 14800 | 20 | 0.78 | cap_P1 | CV 半轴更换费用估算器，输出零件、人工、左右侧差异和是否建议同时检查轴承。 |
| valve cover gasket replacement cost | 18100 | 31 | 0.77 | cap_P1 | 气门室盖垫更换费用估算器，按车型、发动机、地区和是否伴随漏油症状输出价格区间。 |
| fuel pump replacement cost | 18100 | 34 | 0.69 | cap_P1 | 燃油泵更换费用估算器，按车型、地区和零件档位输出总成本与诊断提示。 |
| cost to change fuel pump | 12100 | 37 | 0.69 | cap_P1 | 燃油泵更换费用估算器，输入车型和地区后输出零件、人工、拖车/诊断附加成本。 |
| cabin air filter replacement cost | 12100 | 34 | 0.59 | cap_P1 | 空调滤芯更换费用估算器，给出滤芯价格、人工区间和 DIY 对比。 |

## P1 - OBD 故障码诊断器

- Canonical key: checker/single_entity/obd_code_diagnostic/diagnostic_flow/obd_code_vehicle_symptoms
- Badges: Supply=stable_public_data; Freshness=low; Control=strong; Winner=specialized_data_provider; Permutation=high
- 页面形态：OBD P0171 诊断流程，解释含义并按车型、症状和测试结果给出可能原因与下一步。
- 变现方式：扫描仪/零件联盟、维修线索、广告。
- 为什么值得复核：Priority derived from semantic evidence.
- 关键词条目数：4；总搜索量：112800；最高 CPC：1.56

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| p0456 | 27100 | 24 | 1.56 | none | OBD P0456 诊断流程，按油箱盖、EVAP 泄漏测试和车型常见原因输出排查步骤。 |
| p0301 | 12100 | 22 | 0.98 | none | OBD P0301 诊断流程，结合症状、火花塞/线圈测试和车型信息输出排查顺序。 |
| p0420 | 40500 | 20 | 0.03 | none | OBD P0420 诊断流程，按车型、排气系统症状和传感器测试结果区分氧传感器、排气泄漏和催化转换器问题。 |
| p0171 | 33100 | 29 | 0.03 | none | OBD P0171 诊断流程，解释含义并按车型、症状和测试结果给出可能原因与下一步。 |

## P1 - 胎压监测系统故障排查向导

- Canonical key: workflow/single_entity/tpms_troubleshooting/diagnostic_flow/warning_message_vehicle_tire_sensor_state
- Badges: Supply=user_input_transform; Freshness=low; Control=medium; Winner=community_or_forum; Permutation=medium
- 页面形态：TPMS 故障排查向导，按提示语、胎压状态、传感器年龄和车型输出重置或维修步骤。
- 变现方式：传感器/工具联盟、维修线索、广告。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: maintenance burden is medium and supply control is not strong.
- 关键词条目数：2；总搜索量：26900；最高 CPC：0.74

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| service tire monitor system | 12100 | 29 | 0.74 | cap_P1 | TPMS 故障排查向导，按提示语、胎压状态、传感器年龄和车型输出重置或维修步骤。 |
| tire pressure sensor fault | 14800 | 20 | 0.33 | cap_P1 | 胎压传感器故障诊断器，按警告灯、胎压读数、传感器年龄和车型输出检查/更换建议。 |

## P1 - 汽车电瓶价格与适配估算器

- Canonical key: calculator/single_entity/car_battery_cost/fitment_price_estimate/vehicle_make_model_trim_zip
- Badges: Supply=periodic_public_data; Freshness=periodic; Control=medium; Winner=marketplace; Permutation=high
- 页面形态：按车型匹配电瓶规格，比较 AGM/铅酸价格、保修、安装成本和附近购买选项。
- 变现方式：电瓶联盟、门店线索、广告。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: maintenance burden is medium and supply control is not strong.
- 关键词条目数：1；总搜索量：18100；最高 CPC：0.46

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| car battery cost | 18100 | 38 | 0.46 | cap_P1 | 按车型匹配电瓶规格，比较 AGM/铅酸价格、保修、安装成本和附近购买选项。 |

## P1 - 车载蓝牙故障排查向导

- Canonical key: workflow/single_entity/car_bluetooth_troubleshooting/diagnostic_flow/phone_vehicle_symptom_steps
- Badges: Supply=user_input_transform; Freshness=low; Control=medium; Winner=community_or_forum; Permutation=medium
- 页面形态：车载蓝牙连接诊断器，按手机系统、车型、错误表现和已尝试步骤输出修复路径。
- 变现方式：广告、配件联盟、车机服务线索。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: maintenance burden is medium and supply control is not strong.
- 关键词条目数：1；总搜索量：74000；最高 CPC：0.34

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| bluetooth not connecting to car | 74000 | 27 | 0.34 | cap_P1 | 车载蓝牙连接诊断器，按手机系统、车型、错误表现和已尝试步骤输出修复路径。 |

## P1 - 汽车故障症状诊断流程

- Canonical key: checker/single_entity/vehicle_warning_light_diagnostic/diagnostic_flow/symptom_vehicle_test_results
- Badges: Supply=user_input_transform; Freshness=low; Control=strong; Winner=independent_tool; Permutation=medium
- 页面形态：电瓶灯诊断向导，按启动状态、电压、皮带、发电机测试结果给出下一步检查和维修优先级。
- 变现方式：电瓶/发电机配件联盟、维修线索、广告。
- 为什么值得复核：Priority derived from semantic evidence.
- 关键词条目数：1；总搜索量：12100；最高 CPC：0.29

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| battery light on in car | 12100 | 38 | 0.29 | none | 电瓶灯诊断向导，按启动状态、电压、皮带、发电机测试结果给出下一步检查和维修优先级。 |

## P1 - 汽车养护产品对比选择器

- Canonical key: comparison/single_entity/automotive_maintenance_product/ranked_comparison_table/vehicle_symptom_budget_product_type
- Badges: Supply=subjective_or_ugc; Freshness=periodic; Control=medium; Winner=marketplace; Permutation=medium
- 页面形态：按发动机类型、症状、预算和成分筛选燃油喷嘴清洁剂，输出可解释的产品对比表。
- 变现方式：电商联盟、广告、优惠券。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: maintenance burden is medium and supply control is not strong.
- 关键词条目数：1；总搜索量：14800；最高 CPC：0.25

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| best fuel injector cleaner | 14800 | 31 | 0.25 | cap_P1 | 按发动机类型、症状、预算和成分筛选燃油喷嘴清洁剂，输出可解释的产品对比表。 |

## P1 - 钥匙遥控器电池更换查找器

- Canonical key: lookup/single_entity/key_fob_battery_replacement/fitment_steps/vehicle_make_model_year_fob_type
- Badges: Supply=stable_public_data; Freshness=low; Control=medium; Winner=video_platform; Permutation=high
- 页面形态：钥匙电池型号查找器，返回电池规格、拆装步骤、常见错误和购买链接。
- 变现方式：电池联盟、工具联盟、广告。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: maintenance burden is medium and supply control is not strong.
- 关键词条目数：1；总搜索量：14800；最高 CPC：0.24

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| key fob battery replacement | 14800 | 36 | 0.24 | cap_P1 | 钥匙电池型号查找器，返回电池规格、拆装步骤、常见错误和购买链接。 |

## P1 - 雨刷尺寸适配查找器

- Canonical key: lookup/single_entity/windshield_wiper_size/fitment_table/vehicle_make_model_year
- Badges: Supply=stable_public_data; Freshness=periodic; Control=medium; Winner=marketplace; Permutation=high
- 页面形态：输入年份、品牌、车型后返回前后雨刷尺寸、兼容产品和安装提示。
- 变现方式：雨刷联盟、广告、优惠券。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: maintenance burden is medium and supply control is not strong.
- 关键词条目数：1；总搜索量：14800；最高 CPC：0.19

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| what size windshield wipers do i need | 14800 | 25 | 0.19 | cap_P1 | 输入年份、品牌、车型后返回前后雨刷尺寸、兼容产品和安装提示。 |

## P1 - 发动机故障灯诊断向导

- Canonical key: checker/single_entity/check_engine_light_diagnostic/diagnostic_flow/symptoms_obd_code_vehicle_state
- Badges: Supply=user_input_transform; Freshness=low; Control=medium; Winner=community_or_forum; Permutation=medium
- 页面形态：发动机故障灯诊断向导，先区分闪烁/常亮，再收集 OBD 码和症状，输出风险等级与下一步。
- 变现方式：OBD 扫描仪联盟、维修线索、广告。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: maintenance burden is medium and supply control is not strong.
- 关键词条目数：1；总搜索量：14800；最高 CPC：0.15

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| why is my check engine light on | 14800 | 34 | 0.15 | cap_P1 | 发动机故障灯诊断向导，先区分闪烁/常亮，再收集 OBD 码和症状，输出风险等级与下一步。 |

## P1 - 钥匙遥控器电池更换查找器

- Canonical key: workflow/single_entity/key_fob_battery_replacement/model_specific_steps/vehicle_make_model_year_fob_type
- Badges: Supply=stable_public_data; Freshness=low; Control=medium; Winner=video_platform; Permutation=high
- 页面形态：输入车型年份或钥匙外观后，输出纽扣电池型号、拆装步骤、工具和购买链接。
- 变现方式：电池/工具联盟、广告。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: maintenance burden is medium and supply control is not strong.
- 关键词条目数：1；总搜索量：14800；最高 CPC：0.02

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| how to change battery in key fob | 14800 | 28 | 0.02 | cap_P1 | 输入车型年份或钥匙外观后，输出纽扣电池型号、拆装步骤、工具和购买链接。 |

## P1 - OBD2 扫描仪选择器

- Canonical key: comparison/single_entity/obd2_scanner/guided_product_selector/vehicle_budget_feature_need
- Badges: Supply=periodic_public_data; Freshness=periodic; Control=medium; Winner=marketplace; Permutation=medium
- 页面形态：OBD2 扫描仪选择器，按车型年份、预算、功能需求和手机系统推荐设备类型。
- 变现方式：电商联盟、广告、优惠券。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: maintenance burden is medium and supply control is not strong.
- 关键词条目数：1；总搜索量：22200；最高 CPC：0

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| obd2 scanner for check engine light | 22200 | 32 | 0 | cap_P1 | OBD2 扫描仪选择器，按车型年份、预算、功能需求和手机系统推荐设备类型。 |
