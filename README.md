# 儿童青少年运动与健康 SCI Skill

`youth-exercise-health-sci` 是面向儿童青少年身体活动、运动干预与健康结局研究的 Codex 技能。它把选题、研究设计、公共数据可行性、统计分析、证据综合和投稿准备串成可复核的工作流程，帮助研究者先明确问题与资源，再决定方法。

**English:** A Codex skill for research on physical activity, exercise interventions, and health outcomes in children and adolescents. It supports study design, public-data feasibility, evidence synthesis, and manuscript preparation, with explicit attention to developmental stages, clustered data, measurement, ethics, and reproducibility.

技能尤其面向 Frontiers in Pediatrics 专题 [Physical Activity, Exercise Interventions, and Health Outcomes in Children and Adolescents](https://www.frontiersin.org/research-topics/83941/physical-activity-exercise-interventions-and-health-outcomes-in-children-and-adolescents)，也可按研究问题适配其他期刊。它是独立的研究辅助工具，与 Frontiers 无隶属关系。

[下载完整 ZIP](https://github.com/zararogers338-hash/youth-exercise-health-sci/archive/refs/heads/main.zip) · [阅读技能](skills/youth-exercise-health-sci/SKILL.md) · [检查范围](docs/VALIDATION.md)

## 可以怎样用

| 研究路线 | 技能帮助完成的工作 | 开始前需要确认 |
|---|---|---|
| 运动干预研究 | 定义 PICO、主要结局与时点、FITT-VP 剂量、随机化与整群结构、样本量及实施记录 | 招募场景、独立学校/班级数、对照、伦理、注册与可完成的随访 |
| 观察研究或公共数据分析 | 审计年龄、变量、权限、同人交集与抽样设计，制定分析和验证方案 | 真正可访问的数据、目标年龄的变量覆盖、权重、重复或重叠样本 |
| 系统综述与 Meta 分析 | 确认问题增量、检索与筛选方案、独立研究映射、偏倚评价及可否合并 | 研究可比性、可提取结果、与现有综述的差异 |

配套参考文件覆盖学校、家庭、社区及临床亚群研究，涉及青春期成熟度、可穿戴测量、问卷与健康指标、缺失处理、复杂抽样、整群统计、儿童伦理、英文写作和返修。数据资源文件提供 NHANES、NNYFS、YRBS 和 ICAD 的官方线索及访问限制；这些线索不等于已经取得可分析样本。

## 安装到 Codex

1. 点击上方 ZIP 链接并解压，也可以克隆仓库：

   ```bash
   git clone https://github.com/zararogers338-hash/youth-exercise-health-sci.git
   ```

2. 把仓库内的 **`skills/youth-exercise-health-sci` 整个文件夹**复制到 Codex 的技能目录：

   - 默认位置：`~/.codex/skills/`。
   - Windows 默认位置：`%USERPROFILE%\.codex\skills\`。
   - 如果自定义了 `CODEX_HOME`，则使用 `$CODEX_HOME/skills/`。

3. 确认最终结构是 `skills/youth-exercise-health-sci/SKILL.md`，且 `references`、`assets` 和 `agents` 与它位于同一层级。不要只复制单个 `SKILL.md`。
4. 在 Codex 消息里使用 `$youth-exercise-health-sci`，并提供本次研究的问题、资源或已有材料。

仓库提供技能说明与研究模板，没有附带分析软件环境、个人数据或自动运行的研究流水线。后续统计分析所需的软件与数据访问条件，应随具体方案确定。

## 调用示例

**还没有确定选题：**

```text
使用 $youth-exercise-health-sci，根据“公共数据为主、可补充验证”的资源条件，
比较适合目标特刊的三项儿童青少年运动健康研究问题。
先核实特刊状态与最接近的研究，再列出变量、年龄、访问和验证方面的立项门槛。
```

**已有学校干预条件：**

```text
使用 $youth-exercise-health-sci，帮助设计一项学校运动干预研究。
先根据我提供的学校、班级、年级、干预周期和测量条件，确定随机化单位、
主要结局与时点、FITT-VP、样本量依据，以及伦理和前瞻注册所需材料。
未知条件请标为待确认，不要补造数据。
```

**计划做系统综述：**

```text
使用 $youth-exercise-health-sci，评估某类运动干预对特定年龄儿童健康结局的
系统综述是否有实质增量。先比较近期综述，制定 PICO、检索和偏倚评价方案，
再根据研究独立性与可比性决定是否做 Meta 分析。
```

**已有稿件：**

```text
使用 $youth-exercise-health-sci，审核这份稿件的人群定义、测量、统计、伦理、
证据与结论是否一致，并按目标期刊要求整理需要补充的方法和报告信息。
区分已完成的分析、可用证据、尚待验证的假设及未来计划。
```

## 重要边界

- 面向科研工作，不提供个体患儿运动处方，也不替代伦理审查、统计专业判断或临床决策。
- 区分身体活动、运动干预、体适能和健康结局；横断面关联不能改写为干预效果或因果机制。
- 年龄不能替代实际评估的 Tanner 分期；设备天数、窗口或重复访视不能当作独立儿童数。整群干预应保留学校或班级的依赖结构。
- 公共数据必须核实目标年龄、暴露与结局的同人交集、权重、许可及验证条件。内部拆分与敏感性分析不自动满足外部验证要求。
- 不编造数据、来源、伦理编号、注册信息或作者贡献；不保证阳性结果、创新性、SCI 收录认可或期刊录用。
- 创建或使用技能本身不授权联系编辑、公开数据或提交稿件；此类动作按具体会话中与当前范围相符的授权执行。

## 文件结构

```text
.
├── README.md
├── docs/
│   └── VALIDATION.md
└── skills/
    └── youth-exercise-health-sci/
        ├── SKILL.md
        ├── agents/openai.yaml
        ├── assets/research-records.md
        └── references/
            ├── target-topic.md
            ├── study-design.md
            ├── measurement-analysis.md
            ├── public-data.md
            ├── evidence-synthesis.md
            └── publication-ethics.md
```

[研究记录模板](skills/youth-exercise-health-sci/assets/research-records.md)提供问题与方案卡、FITT-VP 实施卡、数据可行性登记、文献证据台账及变更/返修记录，按当前阶段选用即可。

## 来源快照与更新

本仓库中的专题和数据资源说明沿用技能制作时 **2026-10-16** 的核查快照。该快照记录专题开放投稿、全文截止日期为 **2027-02-08**；这不是实时状态，也不是摘要截止日期。立项和投稿前须重新查看[特刊官方页面](https://www.frontiersin.org/research-topics/83941/physical-activity-exercise-interventions-and-health-outcomes-in-children-and-adolescents)、期刊稿型与方法政策。

来源链接及具体限制见[目标特刊](skills/youth-exercise-health-sci/references/target-topic.md)、[公共数据资源](skills/youth-exercise-health-sci/references/public-data.md)和[发表与伦理](skills/youth-exercise-health-sci/references/publication-ethics.md)。仓库中的检查记录验证的是技能包结构与研究判断边界，不代表已完成原始数据分析、系统综述、临床验证或期刊适配审查。
