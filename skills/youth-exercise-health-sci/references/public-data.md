# 儿童青少年运动研究：公共与可申请数据线索

核查日期：2026-10-16。以下核实了官方文档，**未下载、清洗或审计个体数据**；不是已确认可用的分析样本，也不代表选题已具创新性。正式立项须重新确认访问状态。

## 先过数据审计门槛

为每个候选结局列出“周期、年龄、采集资格、公开资格、变量名、测量方法、权重、个体交集、缺失、重叠队列”。问卷、设备、DXA与生化文件均有记录，不等于同一儿童同时具有这些记录；以官方个体键逐步匹配，检查一对一/一对多关系并报告人数变化。设备分钟数、有效天数、访视数不能作为独立儿童数。

调查研究通常只能提供关联证据；跨周期新样本不是个人随访，设备连续佩戴数天也不等于运动干预。不能把运动测试误称为干预试验。

## 1. NHANES

入口：[数据及文档](https://wwwn.cdc.gov/nchs/nhanes/default.aspx)。全国复杂抽样、重复横断面调查；公共与RDC受限文件并存。

| 线索 | 已核实范围与限制 |
|---|---|
| 2003–04 PAXRAW_C | ≥6岁，右髋ActiGraph AM-7164、单轴、1分钟epoch、7天；睡前及涉水时取下。不能与腕部MIMS直接拼接。 |
| 2011–12 PAXMIN_G | 腕部GT3X+；公开数据≥6岁，2012年采集的3–5岁数据仅RDC。 |
| 2013–14 PAXMIN_H | 腕部GT3X+，≥3岁；分钟级MIMS及算法判定的醒/睡/非佩戴状态，不是现成MVPA分钟。 |
| 2011–12 DXX_G | 全身DXA资格8–59岁；需检查扫描有效性及与PA样本交集，不能把成人骨量诊断阈值直接用于儿童。 |
| 2011–12 GLU_G | 空腹血糖/胰岛素限≥12岁晨间子样本；核对空腹状态、子样本权重及跨周期检测方法。 |
| 2011–12 DPQ_G | PHQ-9虽向≥12岁采集，**公开文件仅≥18岁**；不得据采集年龄承诺12–17岁公开PA—PHQ-9研究。 |

官方代码本：[髋部设备](https://wwwn.cdc.gov/Nchs/Data/Nhanes/Public/2003/DataFiles/PAXRAW_C.htm)、[2011腕部设备](https://wwwn.cdc.gov/Nchs/Data/Nhanes/Public/2011/DataFiles/PAXMIN_G.htm)、[2013腕部设备](https://wwwn.cdc.gov/Nchs/Data/Nhanes/Public/2013/DataFiles/PAXMIN_H.htm)、[DXA](https://wwwn.cdc.gov/Nchs/Data/Nhanes/Public/2011/DataFiles/DXX_G.htm)、[空腹生化](https://wwwn.cdc.gov/Nchs/Data/Nhanes/Public/2011/DataFiles/GLU_G.htm)、[PHQ-9](https://wwwn.cdc.gov/Nchs/Data/Nhanes/Public/2011/DataFiles/DPQ_G.htm)。

以SEQN匹配组件；保留分层、PSU及适用权重。设备分析按文档使用体检权重；加入空腹等子样本时重新确定分析权重，不能仍机械使用全体体检权重。合并周期先核对抽样、测量及权重指南；先建完整调查设计再进行适当年龄域分析。设备过滤记录有效日、佩戴时间、质量标记和阈值来源。

## 2. 2012 National Youth Fitness Survey（NNYFS）

[入口](https://wwwn.cdc.gov/nchs/nhanes/search/nnyfs12.aspx)与[组件/访问等级](https://wwwn.cdc.gov/nchs/nhanes/search/nnyfsdata.aspx)。一次性3–15岁体能调查，有PA问卷、腕部设备、体测及体能组件。问卷3–11岁由代理回答，条目随年龄变化；握力为6–15岁，CEX跑台耐力为6–11岁，CVX心肺适能为12–15岁，不能把两种跑台结果当同一指标。

单独NNYFS有公共文件；敏感项目受限。**NHANES/NNYFS Combined Sample 2012文件及合并权重须RDC**，不可简单拼接两套公共数据冒充官方合并样本。使用NNYFS自身权重、分层和PSU，检查测试的健康与安全排除条件。不得预设有DXA、完整心理量表或血生化；每个结局须在组件表及代码本核实。

## 3. Youth Risk Behavior Survey（YRBS）

[数据](https://www.cdc.gov/yrbs/data/index.html)、[方法](https://www.cdc.gov/yrbs/methods/index.html)、[问卷](https://www.cdc.gov/yrbs/questionnaires/index.html)。全国样本代表美国公私立学校9–12年级在校生，不等同固定12–17岁或所有青少年。自报PA、体育参与和心理行为条目须逐年核实；没有加速度计或实验室测定，心理条目不等于临床诊断。

全国/州/地区文件可下载。核查日官方页面已列2025数据，注明2026-09-21添加。每轮重新抽样；全国样本不是州数据汇总。使用权重、STRATUM、PSU及适当调查方差方法；跨年先核对题目和编码变化，参考[合并指南](https://www.cdc.gov/yrbs/media/pdf/2023/2023_yrbs_combining_data.pdf)。不能简单把各地加总称为全国代表样本。

## 4. International Children’s Accelerometry Database（ICAD）

[现行官网及申请入口](https://studies.epi.ims.cam.ac.uk/icad)、[数据字典](https://epi-meta.mrc-epid.cam.ac.uk/studies/icad/descriptors.shtml)。官网概述覆盖3–18岁，多国设备数据经标准化处理；ICAD2含更多纵向波次，具体年龄与结局仍需按研究核实。

这是需提案审核和数据使用协议的supported access资源，**不是直接开放下载**；遵守获批范围和发表要求，申请时间不作保证。原始研究设计、抽样与变量覆盖不一，不得统一套用NHANES权重或将整个数据库称为干预数据库。

ICAD包含NHANES 2003–04与2005–06；与这些周期进行发现/外部验证前须排除重叠来源并核实人群独立性。跨研究还需统一设备处理、年龄、结局定义，处理研究层级及重复访视相关性。

## 尚未核实的项目

未验证实际文件下载、最终匹配人数、有效佩戴率、缺失模式、各变量分布及所需协变量的共同覆盖；未申请RDC或ICAD权限。以上任何一项影响主要问题时，先完成审计或改题，不以资源总人数替代可分析人数。
