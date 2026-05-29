# HR Deep Research Skill

一个面向人力资源深度研究的 Codex Skill，用于系统研究 HR、HRD、组织能力、组织诊断、人才、绩效、薪酬、激励、文化、干部梯队、员工关系、人力资源知识图谱等议题。

它不是简单的 HR 概念库，而是一套用于把 HR 议题研究到“经营问题、组织机制、方法工具、实践难点、风险控制”的结构化工作流。

## 核心结构

默认研究结构：

```text
思维框架
-> 方法论工具
-> 实践与问题
```

其中“思维框架”进一步拆为：

```text
价值链
-> 关键组织能力
-> 组织形式与组织机制
-> 关键岗位与核心人才
-> HR 机制输出
```

这条链路用于避免 HR 研究直接从业务问题跳到工具清单，而是先回答：

- 企业在哪里创造价值？
- 组织需要具备什么能力？
- 这种能力需要什么组织形式和组织机制承接？
- 哪些关键岗位和核心人才承担这些能力？
- 招聘、薪酬、绩效、激励、培养、继任、文化、员工关系等 HR 机制如何支撑？

## 适用场景

- 组织诊断
- 组织能力建设
- 绩效与薪酬激励研究
- 干部梯队与人才盘点
- 关键岗位识别
- 人力资源知识图谱建设
- HR 制度与机制设计
- CEO/管理层汇报材料
- HR 专题研究报告

## 目录结构

```text
hr-deep-research-skill/
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── hr-domain-lens.md
    └── research-output-templates.md
```

## 安装方式

将整个 `hr-deep-research-skill` 文件夹复制到 Codex skills 目录，并确保文件夹名为 `hr-deep-research`：

```text
~/.codex/skills/hr-deep-research/
```

Windows 示例：

```text
%USERPROFILE%\.codex\skills\hr-deep-research\
```

重启或刷新 Codex 后，即可通过 `$hr-deep-research` 使用。

## 使用示例

```text
使用 $hr-deep-research，深度研究项目工作的人力资源管理
```

```text
使用 $hr-deep-research，研究多品牌多渠道公司如何做组织诊断
```

```text
使用 $hr-deep-research，建立连锁零售企业关键岗位与组织能力的研究框架
```

## 输出特点

这个 skill 会要求研究输出具备：

- 经营问题定义
- 价值链分析
- 关键组织能力识别
- 组织形式与组织机制设计
- 关键岗位与核心人才映射
- HR 机制输出
- 头部咨询公司常用方法论工具
- 数据证据与判断口径
- 实践问题、阻力和风险控制
- 低水平做法 vs 高质量做法

## 许可证

MIT License。
