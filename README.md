<h1 align="center">HR Deep Research Skill / HR 深度研究技能</h1>

<p align="center"><em>「把 HR 问题，研究到能进入经营决策」</em></p>
<p align="center"><em>"Turn HR questions into business-grade research."</em></p>

<p align="center">
  <img alt="License" src="https://img.shields.io/badge/License-MIT-yellow">
  <img alt="Skill" src="https://img.shields.io/badge/Codex-Skill-7B2FF7">
  <img alt="Domain" src="https://img.shields.io/badge/Domain-HR%20Research-blue">
  <img alt="Framework" src="https://img.shields.io/badge/Framework-Value%20Chain%20to%20HR-green">
  <img alt="Bilingual" src="https://img.shields.io/badge/Docs-English%20%2F%20中文-orange">
</p>

<p align="center"><strong>HR Deep Research Skill helps HRDs, consultants, founders, and organization leaders research HR problems from business value to organization mechanisms.</strong></p>
<p align="center"><strong>HR Deep Research Skill 帮助 HRD、咨询顾问、创业者和组织负责人，把 HR 问题从“人力资源模块”研究到“经营价值、组织能力和管理机制”。</strong></p>

**Navigation / 导航**

`How To Use / 使用方法` · `Effect Examples / 效果示例` · `Local Commands / 本地命令` · `Technical Implementation / 技术实现`

## How To Use / 如何使用

Give it an HR topic, industry, company scenario, or management question. It will turn the topic into a structured research workflow instead of a loose concept list.  
输入一个 HR 议题、行业、公司场景或管理问题。它会把问题转成结构化研究流程，而不是松散的概念清单。

For example / 例如：

```text
Deeply research HR management for project-based work.
深度研究项目制工作的人力资源管理。

Research how a multi-brand retail company should conduct organization diagnosis.
研究多品牌零售企业如何做组织诊断。

Build a research framework for key roles and organizational capabilities in chain restaurants.
建立连锁餐饮企业关键岗位与组织能力研究框架。
```

The output is designed for real use: CEO briefings, HRD decision-making, organization diagnosis, policy design, knowledge graphs, and implementation playbooks.  
输出面向真实使用场景：CEO 汇报、HRD 决策、组织诊断、制度设计、知识图谱和落地执行手册。

Main outputs / 主要输出：

```text
research memo                    研究备忘录
issue tree                       问题树
organization diagnosis           组织诊断
HR mechanism design              HR 机制设计
methodology toolkit              方法论工具箱
implementation playbook          落地执行手册
PDF-ready markdown               可转 PDF 的 Markdown
```

## Effect Examples / 效果示例

```text
User / 用户
> 我想研究项目制公司的 HR 管理，重点是绩效、薪酬和人才发展。

HR Deep Research / HR 深度研究
> 先不要从绩效表开始。
> 项目制 HR 的本质问题是：价值创造发生在项目现场，但资源、人才、预算和评价权往往分散在职能部门。
>
> 我会先按这条链条研究：
> Value Chain / 价值链：项目从获客、交付到回款，价值在哪里创造和损失？
> Organizational Capabilities / 组织能力：需要交付复制、跨专业协同、项目风险控制和客户经营能力。
> Organization Mechanisms / 组织机制：项目经理有多大权责？资源如何调度？谁评价项目成员？
> HR Mechanisms / HR机制：绩效、奖金、任职资格、人才池和复盘机制如何围绕项目闭环。
>
> 如果直接设计 KPI，很容易把项目制做成“职能制填表”。
```

```text
User / 用户
> 我们公司人效低，老板让我做一个全面研究。

HR Deep Research / HR 深度研究
> “人效低”不是一个 HR 问题，而是一个经营问题的信号。
> 先拆成四类可能：
> 1. 价值链低效：人花在不创造价值的环节。
> 2. 组织能力不足：增长、交付、复制、协同能力弱。
> 3. 组织机制失灵：权责、决策、流程、预算、问责不清。
> 4. HR机制错配：招聘、绩效、薪酬、培训各做各的。
>
> 研究时我会要求至少拿到：收入/毛利/人力成本、人均产出、流程周期、组织层级、关键岗位负荷、绩效分布和流失数据。
> 没有这些数据，只能写观点，不能支持管理决策。
```

```text
User / 用户
> 想做一个 HR 知识图谱，怎么搭框架？

HR Deep Research / HR 深度研究
> 不要按“招聘、培训、绩效、薪酬”直接建图谱。
> 那只是 HR 模块目录，不是知识图谱。
>
> 我会按“经营问题 -> 组织能力 -> 组织机制 -> 关键岗位 -> HR机制 -> 工具方法 -> 实践问题”建节点。
> 这样每个知识点都能回答：
> 它解决什么经营问题？
> 需要什么组织承接？
> 哪些岗位负责？
> 哪个 HR 模块动作能支撑？
> 落地时常见阻力是什么？
```

## Local Commands / 本地运行命令

Clone and install / 克隆并安装：

```powershell
git clone https://github.com/wangjile200888-eng/hr-deep-research-skill.git
cd hr-deep-research-skill
```

Install into Codex skills / 安装到 Codex skills：

```powershell
$SkillRoot = "$env:USERPROFILE\.codex\skills"
$Target = Join-Path $SkillRoot "hr-deep-research"
New-Item -ItemType Directory -Force -Path $Target | Out-Null
Copy-Item -Recurse -Force SKILL.md,agents,docs,references,LICENSE,README.md $Target
```

Restart Codex, then invoke / 重启 Codex 后调用：

```text
Use $hr-deep-research to deeply research HR management for project-based work.
使用 $hr-deep-research，深度研究项目制工作的人力资源管理。
```

## Technical Implementation / 技术实现

**1. Business-Backed Research Spine / 经营牵引的研究主线**

The skill does not start from HR modules. It starts from business value and translates it step by step into organization and HR mechanisms.  
这个技能不从 HR 模块出发，而是从经营价值出发，一步步翻译成组织机制和 HR 机制。

```text
Value Chain / 价值链
-> Key Organizational Capabilities / 关键组织能力
-> Organization Forms and Mechanisms / 组织形式与组织机制
-> Key Positions and Core Talent / 关键岗位与核心人才
-> HR Mechanism Outputs / HR机制输出
```

This prevents HR research from becoming isolated policy writing. Every conclusion must answer what business problem it solves.  
这能避免 HR 研究变成孤立的制度写作。每个结论都必须回答它解决什么经营问题。

**2. Search Enhancement Protocol / 搜索增强协议**

Search is used to increase research density, not to pile up references.  
搜索用于提高研究密度，而不是堆资料。

```text
Search method / 搜索方法:
business issue x HR topic x methodology x practice problem x counter-evidence
经营问题 x HR议题 x 方法论 x 实践问题 x 反证材料

Search terms / 搜索词:
organization capability, operating model, TOM, RACI, RAPID,
key roles, workforce planning, KPI, OKR, BSC, incentives,
组织能力, 组织诊断, 权责机制, 关键岗位, 人才盘点, 绩效管理, 薪酬激励

Search preference / 搜索偏好:
laws and official data > company filings > consulting methods >
professional associations > academic research > cases > vendor content
法规与官方数据 > 公司公告 > 咨询方法论 > 专业协会 > 学术研究 > 案例 > 供应商文章

Evidence categories / 证据类别:
factual evidence, methodology tools, practice problems, counter-evidence
事实证据、方法论工具、实践问题、反证材料
```

All search findings must be mapped back into the research spine.  
所有搜索结果都必须回填到研究主线中。

**3. Three-Layer Research Framework / 三层研究框架**

Every serious HR topic is expanded into three layers.  
每个重要 HR 议题都展开为三层。

```text
Analytical Framework / 分析框架:
How business value translates into organization and HR mechanisms.
业务价值如何传导到组织与HR机制。

Methodologies and Tools / 方法论与工具:
Value chain, capability map, TOM, RACI/RAPID, key role identification,
talent review, KPI/BSC/OKR, incentive effectiveness analysis.
价值链、组织能力地图、TOM、RACI/RAPID、关键岗位识别、
人才盘点、KPI/BSC/OKR、激励有效性分析。

Practice and Problems / 实践与问题:
Business resistance, data disputes, unclear accountability,
manager capability gaps, change failure, employee relations risk.
业务阻力、数据口径争议、权责不清、管理者能力不足、变革失败、员工关系风险。
```

**4. Node Expansion Protocol / 节点展开协议**

Key nodes cannot be summarized with one sentence. Each node becomes a mini-topic.  
关键节点不能用一句话概括，每个节点都要展开成一个小专题。

```text
Definition / 定义
Business problem / 经营问题
Diagnostic signals / 诊断信号
Data definitions / 数据口径
Organization mechanism / 组织承接
Key roles / 关键岗位
HR mechanisms / HR机制
Practice problems / 实践问题
```

This creates dense, decision-grade HR research instead of generic HR commentary.  
这样产出的不是泛泛 HR 评论，而是有密度、能支持决策的 HR 研究。

## License / 许可证

MIT License.
