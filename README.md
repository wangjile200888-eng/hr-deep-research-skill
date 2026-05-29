# HR Deep Research Skill / 人力资源深度研究技能

一个面向人力资源深度研究的 Codex Skill，用于系统研究 HR、HRD、组织能力、组织诊断、人才、绩效、薪酬、激励、文化、干部梯队、员工关系、人力资源知识图谱等议题。

An open-source Codex Skill for deep HR research, covering HR, HRD, organizational capability, organization diagnosis, talent, performance, compensation, incentives, culture, leadership pipeline, employee relations, and HR knowledge graphs.

它不是简单的 HR 概念库，而是一套用于把人力资源研究纳入“经营问题、组织机制、方法工具、实践难点、风险控制”的结构化工作流。核心包括三部分：

It is not a simple HR concept library. It is a structured workflow for turning HR topics into research outputs that connect business problems, organization mechanisms, methodology tools, implementation challenges, and risk control. The core logic has three parts:

1. **分析框架 / Analytical Framework**：从价值链出发，推导关键组织能力，再进一步推导组织形式与组织机制、关键岗位与核心人才，最后输出招聘配置、培训发展、绩效管理、薪酬激励、员工关系、组织发展/文化等 HR 六大模块机制。  
   Start from the value chain, derive key organizational capabilities, then derive organization forms and mechanisms, key positions and core talent, and finally translate them into HR mechanism outputs across recruitment and staffing, learning and development, performance management, compensation and incentives, employee relations, and organization development/culture.

2. **方法论与工具 / Methodologies and Tools**：使用头部咨询公司和成熟管理实践中的方法论工具，解决分析框架如何落地的问题，例如价值链分析、组织能力地图、Target Operating Model、RACI/RAPID、关键岗位识别、人才盘点、KPI/BSC/OKR、激励有效性分析等。  
   Use mature consulting and management tools to operationalize the framework, such as value chain analysis, organizational capability mapping, target operating model, RACI/RAPID, key position identification, talent review, KPI/BSC/OKR, and incentive effectiveness analysis.

3. **实践与问题 / Practice and Problems**：关注框架和工具在真实组织中可能遇到的阻力与解决方案，例如业务方不认同、组织能力虚化、组织形式选错、权责不清、关键岗位泛化、数据口径争议、变革落地受阻等。  
   Focus on real implementation barriers and solutions, such as business resistance, vague organizational capabilities, wrong organization-form choices, unclear accountability, over-generalized key positions, data definition disputes, and failed change implementation.

同时，这个 skill 默认使用“搜索增强协议”：搜索不是为了堆资料，而是为了提高证据密度、方法论密度、实践问题密度和反证密度。

It also uses a default "search enhancement protocol": search is not for dumping sources, but for increasing evidence density, methodology density, practice-problem density, and counter-evidence density.

此外，skill 会执行“节点展开协议”：每个关键分析节点都必须展开为一个小专题，不能只用一句话或一行表格概括。

It also applies a "node expansion protocol": every key analytical node must be expanded as a mini-topic, not reduced to one sentence or one table row.

## 核心方法论 / Core Methodology

这个 skill 的核心不是“收集 HR 知识点”，而是把人力资源研究拆成三层：

The skill does not merely collect HR knowledge points. It structures HR research into three layers:

```text
一、分析框架 / Analytical Framework
二、方法论与工具 / Methodologies and Tools
三、实践与问题 / Practice and Problems
```

### 一、分析框架 / Analytical Framework

分析框架用于回答：**HR 议题到底如何从业务价值传导到组织与人力资源机制？**

The analytical framework answers: **How does an HR topic connect business value to organization design and HR mechanisms?**

默认链条是：

Default chain:

```text
价值链 / Value Chain
-> 关键组织能力 / Key Organizational Capabilities
-> 组织形式与组织机制 / Organization Forms and Mechanisms
-> 关键岗位与核心人才 / Key Positions and Core Talent
-> HR 机制输出（六大模块） / HR Mechanism Outputs (Six Modules)
```

| 层次 / Layer | 核心问题 / Core Question | 研究重点 / Research Focus |
|---|---|---|
| 价值链 / Value Chain | 企业在哪里创造价值、转化价值、交付价值、损失价值？ / Where does the business create, convert, deliver, or lose value? | 收入、利润、现金流、客户体验、效率、风险 / Revenue, profit, cash flow, customer experience, efficiency, risk |
| 关键组织能力 / Key Organizational Capabilities | 为了承接价值链，组织必须持续具备什么能力？ / What capabilities must the organization repeatedly perform to support the value chain? | 增长、复制、协同、创新、成本控制、客户运营 / Growth, replication, collaboration, innovation, cost control, customer operations |
| 组织形式与组织机制 / Organization Forms and Mechanisms | 这些能力需要什么组织形态和运行机制承接？ / What organization forms and mechanisms should carry these capabilities? | 职能制、事业部制、矩阵制、项目制、区域制、中台、共享服务、敏捷小队；权责、决策、协同、预算、例会、问责 / Functional, BU, matrix, project-based, regional, platform/middle-office, shared services, agile squads; accountability, decisions, collaboration, budgeting, cadence, review mechanisms |
| 关键岗位与核心人才 / Key Positions and Core Talent | 哪些岗位和人才真正承载这些组织能力？ / Which positions and people actually carry these capabilities? | 关键岗位识别、核心人才画像、干部梯队、继任、人才池 / Key position identification, success profiles, leadership pipeline, succession, talent pool |
| HR 机制输出 / HR Mechanism Outputs | HR 如何通过机制把组织能力固化下来？ / How does HR institutionalize organizational capability? | 招聘配置、培训发展、绩效管理、薪酬激励、员工关系、组织发展/文化 / Recruitment and staffing, learning and development, performance management, compensation and incentives, employee relations, OD/culture |

重点：**HR 机制不是起点，而是组织能力和组织形式推导出来的结果。**

Key principle: **HR mechanisms are not the starting point. They are derived from organizational capabilities and organization forms.**

### 二、方法论与工具 / Methodologies and Tools

方法论与工具用于回答：**如何把上述分析框架落到可诊断、可设计、可执行的工作中？**

Methodologies and tools answer: **How can the analytical framework become diagnosable, designable, and executable?**

| 框架环节 / Framework Step | 可使用的方法论与工具 / Tools | 解决的问题 / Problem Solved |
|---|---|---|
| 价值链 / Value Chain | 价值链分析、商业模式拆解、利润模型分析、客户旅程分析 / Value chain analysis, business model decomposition, profit model analysis, customer journey mapping | 找到业务价值创造和损失的位置 / Locate value creation and value leakage |
| 关键组织能力 / Key Organizational Capabilities | 组织能力地图、组织健康诊断、能力差距分析、战略能力分解 / Capability map, organization health diagnosis, capability gap analysis, strategic capability decomposition | 判断组织必须建设什么能力 / Identify required capabilities |
| 组织形式与组织机制 / Organization Forms and Mechanisms | Target Operating Model、RACI/RAPID、组织层级与跨度分析、治理机制设计、敏捷组织模型 / TOM, RACI/RAPID, span-and-layer analysis, governance design, agile organization model | 设计权责、决策、协同和资源配置机制 / Design accountability, decision rights, collaboration, and resource allocation |
| 关键岗位与核心人才 / Key Positions and Core Talent | 关键岗位识别、岗位价值评估、人才盘点、九宫格、能力模型、成功画像 / Key position identification, role valuation, talent review, 9-box, competency model, success profile | 找出承载组织能力的关键岗位和核心人才 / Identify positions and people that carry capabilities |
| HR 机制输出 / HR Mechanism Outputs | KPI/BSC/OKR、薪酬结构设计、激励有效性分析、人才发展体系、继任计划、员工关系风险评估 / KPI/BSC/OKR, compensation structure design, incentive effectiveness analysis, talent development system, succession planning, employee relations risk assessment | 把组织能力固化为 HR 制度和管理动作 / Institutionalize capabilities into HR policies and management actions |

### 三、实践与问题 / Practice and Problems

实践与问题用于回答：**框架和工具落地时会遇到什么真实阻力，以及如何解决？**

Practice and problems answer: **What real obstacles appear during implementation, and how should they be solved?**

| 实践问题 / Practical Problem | 常见表现 / Common Symptoms | 解决方向 / Solution Direction |
|---|---|---|
| 业务方不认同 HR 诊断 / Business does not accept HR diagnosis | 认为 HR 不懂业务，只会套模型 / HR is seen as model-driven but business-blind | 从价值链和经营指标切入，用业务数据证明问题 / Start from value chain and business metrics |
| 组织能力说不清 / Capabilities are vague | 把能力写成口号，如“协同能力”“创新能力” / Capabilities become slogans | 转成可观察行为、流程、岗位和指标 / Translate into behaviors, processes, roles, and metrics |
| 组织形式选错 / Wrong organization form | 盲目上事业部、中台、项目制或矩阵制 / Copying BU, platform, project, or matrix models blindly | 先判断价值链复杂度和组织能力需求 / Choose form after value-chain and capability diagnosis |
| 权责机制不清 / Unclear accountability | 有责任没权力，有权力不承担结果 / Responsibility without power, power without accountability | 用 RACI/RAPID、授权表、例会机制和问责机制澄清 / Clarify through RACI/RAPID, delegation, cadence, and accountability |
| 关键岗位识别泛化 / Key positions are over-generalized | 所有管理岗都被说成关键岗位 / Every management role is called key | 按业务影响、稀缺性、替代成本、风险暴露度筛选 / Filter by business impact, scarcity, replacement cost, and risk exposure |
| HR 机制和组织能力脱节 / HR mechanisms disconnect from capabilities | 招聘、绩效、薪酬、培训各做各的 / HR modules work separately | 让六大模块围绕同一组组织能力和关键岗位联动 / Align six HR modules around capabilities and key roles |
| 数据口径争议 / Data definition disputes | 人效、绩效、成本、流失率各部门口径不同 / Different departments use different definitions | 统一指标定义、数据来源和使用场景 / Align definitions, data sources, and use cases |
| 变革落地受阻 / Change implementation stalls | 干部表态支持，实际不执行 / Leaders agree verbally but do not execute | 建立试点、沟通、利益调整、节奏控制和复盘机制 / Use pilots, communication, interest adjustment, pacing, and review |

### 搜索增强协议 / Search Enhancement Protocol

高质量 HR 研究需要增加“有效搜索密度”，而不是简单增加搜索量。

High-quality HR research requires higher effective search density, not simply more search volume.

| 搜索类别 / Search Category | 作用 / Purpose | 典型来源 / Typical Sources |
|---|---|---|
| 事实证据 / Factual Evidence | 支撑判断和结论 / Support judgments and conclusions | 法规、行业数据、公司公告、研究报告 / Regulations, industry data, company filings, research reports |
| 方法论工具 / Methodology Tools | 让框架可落地 / Make the framework operational | 头部咨询公司、专业协会、管理实践 / Consulting firms, professional bodies, management practices |
| 实践问题 / Practice Problems | 揭示真实阻力 / Reveal real implementation barriers | 企业案例、复盘文章、失败案例、管理访谈 / Company cases, retrospectives, failure cases, management interviews |
| 反证材料 / Counter-Evidence | 修正结论边界 / Correct conclusion boundaries | 批评观点、不适用条件、失败案例 / Criticism, non-applicable contexts, failure cases |

搜索结果必须回填到主框架中：

Search findings must be mapped back into the core framework:

```text
搜索材料 / Search findings
-> 价值链 / Value Chain
-> 关键组织能力 / Key Organizational Capabilities
-> 组织形式与组织机制 / Organization Forms and Mechanisms
-> 关键岗位与核心人才 / Key Positions and Core Talent
-> HR 机制输出 / HR Mechanism Outputs
-> 实践问题与风险控制 / Practice Problems and Risk Control
```

### 节点展开协议 / Node Expansion Protocol

为提高分析密度，每个关键分析节点都要按 8 项展开：

To increase analytical density, every key node should be expanded across eight dimensions:

| 展开项 / Dimension | 要回答的问题 / Question |
|---|---|
| 定义 / Definition | 这个概念到底指什么？ / What does this concept mean? |
| 经营问题 / Business Problem | 它解决什么增长、利润、效率、客户体验或风险问题？ / What growth, profit, efficiency, customer, or risk problem does it solve? |
| 诊断信号 / Diagnostic Signals | 如何判断这里有问题？ / How do we know this node is weak? |
| 数据口径 / Data Definitions | 需要哪些数据验证？ / What data is needed for validation? |
| 组织承接 / Organization Mechanism | 需要什么组织形式、权责、协同或决策机制？ / What organization form, accountability, collaboration, or decision mechanism is required? |
| 关键岗位 / Key Roles | 谁负责，谁最关键？ / Who owns it and who is critical? |
| HR 机制 / HR Mechanisms | 招聘、培训、绩效、薪酬、员工关系、OD/文化如何支撑？ / How do HR modules support it? |
| 实践问题 / Practice Problems | 会遇到什么阻力，如何解决？ / What resistance appears and how should it be solved? |

密度阈值：

Density threshold:

- 至少 3 个诊断信号 / At least 3 diagnostic signals
- 至少 5 个数据口径 / At least 5 data definitions
- 至少 2 个组织机制 / At least 2 organization mechanisms
- 至少 3 个关键岗位或关键角色 / At least 3 key positions or roles
- HR 六大模块中至少 4 个模块要有机制动作 / At least 4 of the 6 HR modules should have mechanism actions
- 至少 2 个实践阻力与解决方案 / At least 2 implementation barriers and solutions

## 适用场景 / Use Cases

- 组织诊断 / Organization diagnosis
- 组织能力建设 / Organizational capability building
- 绩效与薪酬激励研究 / Performance, compensation, and incentive research
- 干部梯队与人才盘点 / Leadership pipeline and talent review
- 关键岗位识别 / Key position identification
- 人力资源知识图谱建设 / HR knowledge graph building
- HR 制度与机制设计 / HR policy and mechanism design
- CEO/管理层汇报材料 / CEO or management presentation materials
- HR 专题研究报告 / HR research reports

## 目录结构 / Folder Structure

```text
hr-deep-research-skill/
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── hr-domain-lens.md
    └── research-output-templates.md
```

## 安装方式 / Installation

将整个 `hr-deep-research-skill` 文件夹复制到 Codex skills 目录，并确保文件夹名为 `hr-deep-research`：

Copy the full `hr-deep-research-skill` folder into your Codex skills directory and rename the folder to `hr-deep-research`:

```text
~/.codex/skills/hr-deep-research/
```

Windows 示例 / Windows example:

```text
%USERPROFILE%\.codex\skills\hr-deep-research\
```

重启或刷新 Codex 后，即可通过 `$hr-deep-research` 使用。

Restart or refresh Codex, then invoke the skill with `$hr-deep-research`.

## 使用示例 / Usage Examples

```text
使用 $hr-deep-research，深度研究项目工作的人力资源管理
Use $hr-deep-research to deeply research HR management for project-based work.
```

```text
使用 $hr-deep-research，研究多品牌多渠道公司如何做组织诊断
Use $hr-deep-research to study how multi-brand, multi-channel companies should conduct organization diagnosis.
```

```text
使用 $hr-deep-research，建立连锁零售企业关键岗位与组织能力的研究框架
Use $hr-deep-research to build a research framework for key positions and organizational capabilities in chain retail.
```

## 输出特点 / Output Characteristics

这个 skill 会要求研究输出具备：

The skill encourages research outputs to include:

- 经营问题定义 / Business problem definition
- 价值链分析 / Value chain analysis
- 关键组织能力识别 / Key organizational capability identification
- 组织形式与组织机制设计 / Organization form and mechanism design
- 关键岗位与核心人才映射 / Key position and core talent mapping
- HR 机制输出（招聘配置、培训发展、绩效管理、薪酬激励、员工关系、组织发展/文化） / HR mechanism outputs across the six modules
- 头部咨询公司常用方法论工具 / Mature consulting methodology tools
- 数据证据与判断口径 / Data evidence and judgment criteria
- 实践问题、阻力和风险控制 / Practical problems, resistance, and risk control
- 低水平做法 vs 高质量做法 / Low-quality practices vs high-quality practices

## 许可证 / License

MIT License.
