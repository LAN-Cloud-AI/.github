# 兰芯云朵 · LAN Cloud AI

**用 AI 重新定义汽车零售与售后怎么被经营。**  
**Redefining how automotive retail and aftersales are operated — with AI.**

我们把「看见 → 理解 → 调度 → 判断」拆成可落地的产品能力：从公域信号里发现机会，从客户关系里识别风险，从车间流转里预测延误——再把动作送到正确的人手里。

We turn *See → Understand → Orchestrate → Judge* into shippable product capabilities: discover opportunity in public signals, surface risk in customer relationships, anticipate delay on the shop floor — then route the next action to the right person.

> **造法 / Method：** 业务规则 × 多维表格 / 事件系统 × AI · Business rules × multidimensional tables / event systems × AI  
> **路径 / Path：** 先在真实门店验证，再契约先行地 SaaS 化 · Prove in real stores, then SaaS-ify behind contracts

[中文](#能力地图--capability-map) · [English](#capability-map)

---

## 能力地图 · Capability Map

```text
创造 Create · AIGC
   ↓
看见 See · LeadsHunter     公域内容 → 经营信号 → 可执行线索
                           Public content → business signals → actionable leads
理解 Understand · VECT     碎片数据 → 关系温度 → 风险与责任动作
                           Fragmented data → relationship temperature → risk & accountable actions
调度 Orchestrate · TACT    车间工单 → 可信状态 → 可解释派工与时效预警
                           Work orders → trusted state → explainable dispatch & timing alerts
判断 Judge · AI Analyst    可信样本 → 反常识洞察 → 分层行动
                           Trusted samples → counter-intuitive insights → layered actions
```

| 产品 Product | 一句话 One-liner | 状态 Status |
| --- | --- | --- |
| **[LeadsHunter](https://github.com/LAN-Cloud-AI/leadsHunter)** | 客户并没有沉默，他只是没在你的 CRM 里说话<br>*Customers aren’t silent — they just aren’t speaking inside your CRM.* | 生产运行 In production（Mercury） |
| **VECT** | 客户说「没事」，系统却看见他正在离开<br>*They say “it’s fine” — the system sees they’re leaving.* | 飞书验证 → SaaS 筹备<br>*Feishu-proven → SaaS prep* |
| **[TACT](https://github.com/LAN-Cloud-AI/TACT)** | 车辆还没延误，系统已经看见延误会在哪里发生<br>*The car isn’t late yet — the system already sees where delay will form.* | 飞书验证 → Phase 0 契约 / SaaS 启动<br>*Feishu-proven → Phase 0 contracts / SaaS underway* |

---

<a id="capability-map"></a>

## 精选仓库 · Featured Repositories

### 公域线索 · LeadsHunter

面向经销商销售团队的公域线索采集、AI 识别与交付：抖音 / 小红书等内容进池，Agent 判断意向，再按组织完成指派、飞书分发与短链交付。

Public-domain lead capture, AI scoring, and delivery for dealer sales teams: ingest Douyin / Xiaohongshu content, score intent with an Agent, then assign by organization and deliver via Feishu cards and short links.

| 仓库 Repo | 说明 Description | 可见性 Visibility |
| --- | --- | --- |
| [leadsHunter](https://github.com/LAN-Cloud-AI/leadsHunter) | 采集、任务引擎、多租户 RBAC、线索池与交付（Mercury）<br>*Ingestion, job engine, multi-tenant RBAC, lead pool & delivery (Mercury)* | Private |
| [LH_evaluation_agent](https://github.com/LAN-Cloud-AI/LH_evaluation_agent) | 评论 / 帖子双管线评分 Agent<br>*Comment & post dual-pipeline scoring Agent* | Private |
| [LH_Training_Ground](https://github.com/LAN-Cloud-AI/LH_Training_Ground) | 场景（行业）+ 产品 SKU 训练场；Skill 可同步回生产<br>*Scenario (industry) + product SKU training ground; skills sync to prod* | Public |
| [leadsHunter_APP](https://github.com/LAN-Cloud-AI/leadsHunter_APP) | Expo 移动端：线索、推送与外链唤起<br>*Expo mobile app: leads, push, deep links* | Private |

### 售后智能 · Aftersales Intelligence · VECT × TACT

从飞书多维表格长出来的门店经营方法：VECT 经营客户关系，TACT 编排车间工单。共用六要素——**业务对象 · 状态 · 责任人 · 时点 · 证据 · 风险**。

Born from Feishu multidimensional tables: VECT runs customer relationships; TACT orchestrates workshop work orders. Shared six pillars — **object · state · owner · timing · evidence · risk**.

| 仓库 Repo | 说明 Description | 可见性 Visibility |
| --- | --- | --- |
| [TACT](https://github.com/LAN-Cloud-AI/TACT) | 多门店工单编排 Phase 0 契约：Schema、RuleSet、权限、事件不变量与合成验收<br>*Multi-store work-order orchestration Phase 0 contracts* | Public |
| VECT（筹备中 / in prep） | 客户生命周期精准管理：全功能档案、AI 质检、雷达预警、责任闭环<br>*Customer lifecycle precision management* | — |

### 内部运营 · Internal Ops

| 仓库 Repo | 说明 Description | 可见性 Visibility |
| --- | --- | --- |
| [LAN_Cloud_Internal_Expense](https://github.com/LAN-Cloud-AI/LAN_Cloud_Internal_Expense) | 订阅资产与报销：Workers / D1 / R2 + Access；飞书 Base 只读导入<br>*Subscriptions & reimbursements; Feishu Base as read-only import* | Public |

---

## 我们相信什么 · What We Believe

1. **AI 的第一份工作不是画图，是决定哪些数据值得相信。**  
   *AI’s first job isn’t charting — it’s deciding which data deserves trust.*

2. **看见风险还不够，必须把动作送到正确岗位。**  
   *Seeing risk isn’t enough — the action must reach the right role.*

3. **自动化必须可解释、可审计；高风险动作保留人工与 Owner 确认。**  
   *Automation must be explainable and auditable; high-risk actions stay human- and owner-gated.*

4. **先在真实业务跑通，再用契约把门，再谈规模化开通。**  
   *Prove in real operations, lock the gates with contracts, then scale SaaS access.*

---

## 协作与边界 · Collaboration & Boundaries

- 公开仓库欢迎阅读、讨论与 Issue；含业务密钥、生产数据或未授权连接的改动不会被接受。  
  *Public repos welcome reading, discussion, and Issues. Changes involving business secrets, production data, or unauthorized connectivity will not be accepted.*

- LeadsHunter 等生产链路为私有仓；训练场与契约仓优先作为对外理解入口。  
  *Production paths such as LeadsHunter are private; training grounds and contract kits are the preferred public entry points.*

- TACT / VECT 的 Phase 0 校验通过，不代表生产功能或生产连接已授权。  
  *Passing Phase 0 checks for TACT / VECT does not authorize production features or production connectivity.*

---

<p align="center">
  <sub>兰芯云朵 · LAN Cloud AI</sub><br/>
  <sup>以前，我们一起解决问题。现在，一起重新定义问题怎么解决。</sup><br/>
  <sup><em>We used to solve problems together. Now we redefine how problems get solved.</em></sup>
</p>
