# SERP 复核推荐词簇

二筛候选来源数：9
推荐词簇数：5
推荐关键词条目数：9

| 优先级 | 词簇数 | 关键词条目数 |
| --- | ---: | ---: |
| P0 | 0 | 0 |
| P1 | 3 | 7 |
| P2 | 2 | 2 |

优先级说明：
- P0：优先复核；供给可控、维护有界、差异化清楚，且不是由排列组合搜索量硬抬上来。
- P1：随后复核；机会成立，但数据供给、自然赢家或执行成本还需要确认。
- P2：长尾、cluster seed 或需数据源确认；不是自动拒绝。

## P1 - vehicle wrap cost estimator

- Canonical key: calculator/none/vehicle_wrap_cost/cost_estimator/vehicle_size_wrap_type_coverage_location
- Badges: Supply=periodic_public_data; Freshness=periodic; Control=medium; Winner=independent_tool; Permutation=low
- 页面形态：按车型尺寸、全车/局部包膜、材料等级和地区生成价格区间，并给出拆项明细和询价清单。
- 变现方式：广告、贴膜店线索、材料/护理用品联盟、报价表模板。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: maintenance burden is medium and supply control is not strong.
- 关键词条目数：1；总搜索量：14800；最高 CPC：1.11

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| car wrap cost | 14800 | 20 | 1.11 | cap_P1 | 按车型尺寸、全车/局部包膜、材料等级和地区生成价格区间，并给出拆项明细和询价清单。 |

## P1 - OBD-II trouble code diagnostic workflow

- Canonical key: checker/single_entity/obd_ii_trouble_code_diagnostic/diagnostic_flow/obd_code_optional_vehicle_make_model_symptoms
- Badges: Supply=stable_public_data; Freshness=low; Control=medium; Winner=independent_tool; Permutation=high
- 页面形态：OBD代码检查器，输入代码、车型和症状后输出含义、可能原因、排查顺序、维修难度和常见费用。
- 变现方式：广告、OBD扫描仪联盟、零件联盟、维修线索。
- 为什么值得复核：Priority derived from semantic evidence.
- 关键词条目数：5；总搜索量：94900；最高 CPC：0.98

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| p0301 | 12100 | 22 | 0.98 | none | OBD代码检查器，输入代码、车型和症状后输出含义、可能原因、排查顺序、维修难度和常见费用。 |
| p0113 | 12100 | 29 | 0.33 | none | OBD代码检查器，输入代码、车型和症状后输出含义、可能原因、排查顺序、维修难度和常见费用。 |
| p0302 | 12100 | 24 | 0.22 | none | OBD代码检查器，输入代码、车型和症状后输出含义、可能原因、排查顺序、维修难度和常见费用。 |
| p0455 | 18100 | 22 | 0.04 | none | OBD代码检查器，输入代码、车型和症状后输出含义、可能原因、排查顺序、维修难度和常见费用。 |
| p0420 | 40500 | 20 | 0.03 | none | OBD代码检查器，输入代码、车型和症状后输出含义、可能原因、排查顺序、维修难度和常见费用。 |

## P1 - auto repair cost estimator

- Canonical key: calculator/single_entity/auto_repair_cost/repair_cost_estimator/repair_type_vehicle_make_model_year_labor_location
- Badges: Supply=periodic_public_data; Freshness=periodic; Control=medium; Winner=specialized_data_provider; Permutation=medium
- 页面形态：输入车型年份、地区和OEM/副厂零件偏好后，输出零件、工时、税费和总价区间，并附维修前检查步骤。
- 变现方式：维修线索、零件联盟、广告、诊断清单下载。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: natural winner is strong, but independent differentiation is credible.
- 关键词条目数：1；总搜索量：14800；最高 CPC：0.97

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| cost to change catalytic converter | 14800 | 39 | 0.97 | cap_P1 | 输入车型年份、地区和OEM/副厂零件偏好后，输出零件、工时、税费和总价区间，并附维修前检查步骤。 |

## P2 - vehicle resale value estimator

- Canonical key: calculator/single_entity/vehicle_resale_value/valuation_estimator/make_model_year_trim_mileage_condition_location
- Badges: Supply=live_external_data; Freshness=live; Control=weak; Winner=specialized_data_provider; Permutation=high
- 页面形态：按年份、里程、配置、车况和地区估算Tacoma转售价值，并显示市场区间、折旧趋势和挂牌样本。
- 变现方式：二手车线索、估值报告、广告、车商/保险联盟。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: dynamic or official data with weak/unknown supply control; live freshness with high/unknown maintenance burden; high permutation inflation with weak/unknown canonical supply.
- 关键词条目数：1；总搜索量：12100；最高 CPC：1.5

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| toyota tacoma resale value | 12100 | 26 | 1.5 | cap_P2 | 按年份、里程、配置、车况和地区估算Tacoma转售价值，并显示市场区间、折旧趋势和挂牌样本。 |

## P2 - vehicle model quarterly sales lookup

- Canonical key: data_page/entity_date/vehicle_model_sales/historical_data_table/vehicle_model_quarter_year
- Badges: Supply=periodic_public_data; Freshness=periodic; Control=unknown; Winner=official_source; Permutation=high
- 页面形态：车型季度销量查询页，展示该季度数值、同比/环比、历史趋势和同级车型对比。
- 变现方式：广告、汽车行业数据订阅、研究报告下载。
- 为什么值得复核：Priority derived from semantic evidence; cap applied: high permutation inflation with weak/unknown canonical supply.
- 关键词条目数：1；总搜索量：14800；最高 CPC：0

| 关键词 | 搜索量 | KD | CPC | Cap | 推荐页面形态 |
| --- | ---: | ---: | ---: | --- | --- |
| lincoln aviator q2 2025 sales | 14800 | 21 | 0 | cap_P2 | 车型季度销量查询页，展示该季度数值、同比/环比、历史趋势和同级车型对比。 |
