<!-- ELUCENIA technical documentation · fleischner-2017 · zh · no clinical/professional/rights approval -->

# Fleischner 2017（实性肺结节）

[条件、来源与许可](https://elucenia.org/zh/tools/fleischner-2017)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 结节平均直径（多发时为最可疑的结节）

`tamanho`

mm · 范围: 1–30

### 结节数

`num`

- `u` — 单个
- `m` — 多个

### 肺癌风险

`risco`

- `b` — 低
- `a` — 高（吸烟、年龄、暴露、家族史、肺气肿、上叶）

## 方法版本

Fleischner Society 2017：偶发实性结节，平均直径取整；保留排除条件

## 已记录的公式

平均直径 = (长轴 + 短轴) ÷ 2，四舍五入至最近毫米。范围：\< 6 mm（\< 100 mm³），6至8 mm（100至250 mm³），\> 8 mm（\> 250 mm³）。

## 限制与适用人群

本版本用于35岁及以上成人偶然发现的实性肺结节。Fleischner2017建议不适用于肺癌筛查、免疫功能受损者或已知原发癌的患者。亚实性或部分实性结节需要使用另一套算法。存在多个结节时，应以最可疑的结节指导评估；它不一定是最大的结节。风险分层和随访决定取决于临床及影像学评估。

## 参考文献

- [MacMahon H et al. Guidelines for management of incidental pulmonary nodules detected on CT images: from the Fleischner Society 2017. Radiology, 2017.](https://doi.org/10.1148/radiol.2017161659)

- [MacMahon et al. Radiology2017, DOI10.1148/radiol.2017161659](https://pubs.rsna.org/doi/full/10.1148/radiol.2017161659)

- [Original sixteen-page RSNA article, institutional copy at University of Wisconsin](https://wiki.radiology.wisc.edu/images/b/b9/Flesichner_Guidelines_2017.pdf)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 已记录的结果

以下信息保留该方法对合成示例的输出，不构成独立的临床验证。

### 1

无需常规随访

| 结果详情 | |
| --- | --- |
| 患者风险 | 低 |
| 四舍五入的平均直径 | 4 mm |

不适用于 35 岁以下人群、已知癌症患者、免疫抑制患者或肺癌筛查（使用 Lung-RADS）。


### 2

6至12个月后行CT检查，然后在18至24个月后再行CT检查

| 结果详情 | |
| --- | --- |
| 患者风险 | 高 |
| 四舍五入的平均直径 | 6 mm |

不适用于 35 岁以下人群、已知癌症患者、免疫抑制患者或肺癌筛查（使用 Lung-RADS）。


### 3

3至6个月后行CT检查；然后考虑在18至24个月后行CT检查

| 结果详情 | |
| --- | --- |
| 患者风险 | 低 |
| 四舍五入的平均直径 | 7 mm |

不适用于 35 岁以下人群、已知癌症患者、免疫抑制患者或肺癌筛查（使用 Lung-RADS）。


### 4

考虑3个月后行CT、PET-CT或组织样本

| 结果详情 | |
| --- | --- |
| 患者风险 | 低 |
| 四舍五入的平均直径 | 10 mm |

不适用于 35 岁以下人群、已知癌症患者、免疫抑制患者或肺癌筛查（使用 Lung-RADS）。

