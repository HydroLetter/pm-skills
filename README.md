# PM-Skills — 产品经理 AI Skill 知识体系

> 一套覆盖产品经理全链路的 AI Skill 集合，从需求分析到项目管理，从架构设计到商业策略，每个 Skill 对应 PM 工作的一个核心领域。

📁 [github.com/HydroLetter/pm-skills](https://github.com/HydroLetter/pm-skills)

---

## 模块总览

| # | 模块 | 定位 | 一句话 |
|:--:|------|------|--------|
| 1 | `pm-thinking-models` | 🧠 思维模型 | 15个PM核心思考框架速查（SWOT/KANO/SMART/波特五力…） |
| 2 | `pm-requirements` | 📋 需求分析 | 从用户访谈到PRD输出的完整需求分析流程 |
| 3 | `pm-strategy` | 🎯 策略工具 | 定价/竞品分析/数据分析/自检清单 |
| 4 | `pm-design-dev` | 🎨 设计研发 | 原型设计→PRD→敏捷开发→质量管理的研发全流程 |
| 5 | `pm-workflow` | 🔄 项目管理 | 从市场判断到上线复盘的全生命周期项目管理框架 |
| 6 | `pm-architecture-framework` | 🏗️ 架构设计 | 分层架构/中台/微服务/ESB等平台级架构设计方法论 |
| 7 | `pm-architecture-cases` | 📚 架构案例 | 19+个真实行业产品架构案例（电商/金融/AI/物联网…） |
| 8 | `pm-operations` | 📊 产品运营 | 指标体系/用户增长/生命周期/渠道运营/活动策划 |
| 9 | `pm-toolkit` | 🧰 资源工具箱 | PM成长路线/必备工具/书单/商业模式/简历面试 |

---

## 各模块详解

### 1. pm-thinking-models · 15个核心思维模型

覆盖 4 大类别：

| 类别 | 模型 |
|------|------|
| 万能通用 | SMART · MECE · 5W2H |
| 市场分析 | PEST · 波士顿矩阵 · SWOT · 波特五力 |
| 产品运营 | 用户体验要素 · 马斯洛 · KANO · 产品画布 · AARRR |
| 个人成长 | 四象限法则 · 金字塔原理 · KISS复盘 |

---

### 2. pm-requirements · 需求分析全流程

- 需求分析 8 步标准化流程（用户访谈→MRD/PRD）
- KANO 模型 5 种需求类型及产品策略
- 价值-成本四象限优先级排序
- 算法产品需求分析专项

---

### 3. pm-strategy · 策略工具箱

- **定价**：六步法 + 7种定价模型 + 验证清单
- **竞品分析**：六步法 + 6维度框架 + 输出模板
- **PM自检清单**：5套（需求/设计/开发/上线前/上线后）
- **数据分析**：四步法 + 5个常见陷阱

---

### 4. pm-design-dev · 设计研发流程

- 7 阶段产品设计全流程（需求确认→交付研发）
- PM 技术知识体系（前端/后端/数据）
- Scrum 敏捷开发框架
- BUG 五级严重等级定义

---

### 5. pm-workflow · 项目管理全流程

- 6 阶段全生命周期（市场判断→需求管理→需求确认→项目执行→项目验收→项目上线）
- 8 个核心角色 × 8 个阶段产出物矩阵
- 需求变更流程（4级优先级决策矩阵）
- 8 条项目管理硬性规范

---

### 6. pm-architecture-framework · 架构设计方法论

- 四步架构设计法 + 功能矩阵（MECE原则）
- 经典四层架构 · 微服务架构 · 中台架构（业务/数据/AI）
- ESB 企业服务总线 · 企业 IT 系统架构
- 架构图 4 种类型及绘制规范

---

### 7. pm-architecture-cases · 架构案例库

7 大行业赛道，19+ 真实案例：

| 赛道 | 案例 |
|------|------|
| 电商零售 | 电商平台 / 供应链 / 无人便利店 / 有赞生态 |
| 金融支付 | 支付平台 / 银行系统 / 汽车金融 / 现金贷 |
| AI 智能 | AI 医疗 / 人脸识别 / AR / 物联网中台 |
| 企业应用 | 不动产管理 / 门户系统 / 投放平台 |
| 安全风控 | 防火墙 / 安全平台 / 风控系统 |

---

### 8. pm-operations · 运营实战指南

- APP 运营指标金字塔（北极星→增长→活跃→营收）
- 用户增长引擎 + 5 种裂变玩法
- 用户生命周期 5 阶段 × RFM 8 分群模型
- 6 类渠道特征对比 + 6 种活动类型
- 运营数据分析 4 层框架

---

### 9. pm-toolkit · 资源工具箱

- PM 成长路线（4阶段） + AI PM 专项学习路线（~70天）
- 29+ 款工具推荐（原型/思维导图/文档/项目管理/数据分析）
- 15 种商业模式详解
- PM 推荐书单（15本）+ 简历面试指南（STAR法则）

---

## 使用方式

每个模块的入口文件为 `SKILL.md`，可通过 CodeBuddy 等 AI 编程助手的 Skill 系统加载：

```bash
# 示例：加载需求分析 Skill
@command://pm-requirements
```

各模块既可独立使用，也可按 PM 工作阶段组合调用：

```
需求阶段：thinking-models → requirements
设计阶段：strategy → architecture-framework → architecture-cases
研发阶段：design-dev → workflow
运营阶段：operations → strategy
求职成长：toolkit
```

---

## 目录结构

```
pm-skills/
├── pm-thinking-models/      # 15个思维模型速查
├── pm-requirements/          # 需求分析全流程
├── pm-strategy/              # 策略工具箱
├── pm-design-dev/            # 设计研发流程
├── pm-workflow/              # 项目管理全流程
├── pm-architecture-framework/ # 架构设计方法论
├── pm-architecture-cases/    # 架构案例库
├── pm-operations/            # 运营实战指南
├── pm-toolkit/               # 资源工具箱
├── pm-skills/                # 总容器
└── README.md                 # 本文档
```
