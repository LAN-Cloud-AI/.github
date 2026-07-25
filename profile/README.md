# 兰芯云朵 · LAN Cloud AI

[English](./README.en.md)

**用 AI 重新定义汽车零售与售后怎么被经营。**

我们把「看见 → 理解 → 调度 → 判断」拆成可落地的产品能力：从公域信号里发现机会，从客户关系里识别风险，从车间流转里预测延误——再把动作送到正确的人手里。

> 造法一句话：**业务规则 × 多维表格 / 事件系统 × AI**  
> 先在真实门店验证，再契约先行地 SaaS 化。

---

## 能力地图

```text
创造 · AIGC
   ↓
看见 · LeadsHunter          公域内容 → 经营信号 → 销售可执行线索
理解 · VECT                 碎片客户数据 → 关系温度 → 风险与责任动作
调度 · TACT                 车间工单 → 可信状态 → 可解释派工与时效预警
判断 · AI Analyst / Agent   可信样本 → 反常识洞察 → 分层行动
```

| 产品 | 一句话 | 状态 |
| --- | --- | --- |
| **[LeadsHunter](https://github.com/LAN-Cloud-AI/leadsHunter)** | 客户并没有沉默，他只是没在你的 CRM 里说话 | 生产运行（Mercury） |
| **VECT** | 客户说「没事」，系统却看见他正在离开 | 飞书验证 → SaaS 筹备 |
| **[TACT](https://github.com/LAN-Cloud-AI/TACT)** | 车辆还没延误，系统已经看见延误会在哪里发生 | 飞书验证 → Phase 0 契约 / SaaS 启动 |

---

## 精选仓库

### 公域线索 · LeadsHunter

面向经销商销售团队的公域线索采集、AI 识别与交付系统：抖音 / 小红书等内容进池，Agent 判断意向，再按组织完成指派、飞书分发与短链交付。

| 仓库 | 说明 | 可见性 |
| --- | --- | --- |
| [leadsHunter](https://github.com/LAN-Cloud-AI/leadsHunter) | 采集、任务引擎、多租户 RBAC、线索池与交付（Mercury 稳定版） | Private |
| [LH_evaluation_agent](https://github.com/LAN-Cloud-AI/LH_evaluation_agent) | 评论 / 帖子双管线评分 Agent（意向、摘要、证据、跟进建议） | Private |
| [LH_Training_Ground](https://github.com/LAN-Cloud-AI/LH_Training_Ground) | 场景（行业）+ 产品 SKU 的模型训练场；Skill 可同步回生产 | Public |
| [leadsHunter_APP](https://github.com/LAN-Cloud-AI/leadsHunter_APP) | Expo 移动端：线索、推送与外链唤起 | Private |

### 售后智能 · VECT × TACT

从飞书多维表格长出来的门店经营方法：VECT 经营客户关系，TACT 编排车间工单。共用六要素——**业务对象 · 状态 · 责任人 · 时点 · 证据 · 风险**。

| 仓库 | 说明 | 可见性 |
| --- | --- | --- |
| [TACT](https://github.com/LAN-Cloud-AI/TACT) | 多门店工单编排 Phase 0 契约：Schema、RuleSet、权限、事件不变量与合成验收 | Public |
| VECT（筹备中） | 客户生命周期精准管理：全功能档案、AI 质检、雷达预警、责任闭环 | — |

### 内部运营

| 仓库 | 说明 | 可见性 |
| --- | --- | --- |
| [LAN_Cloud_Internal_Expense](https://github.com/LAN-Cloud-AI/LAN_Cloud_Internal_Expense) | 订阅资产与报销：Cloudflare Workers / D1 / R2 + Access；飞书 Base 只读导入 | Public |

---

## 我们相信什么

1. **AI 的第一份工作不是画图，是决定哪些数据值得相信。**  
2. **看见风险还不够，必须把动作送到正确岗位。**  
3. **自动化必须可解释、可审计；高风险动作保留人工与 Owner 确认。**  
4. **先在真实业务跑通，再用契约把门，再谈规模化开通。**

---

## 协作与边界

- 公开仓库欢迎阅读、讨论与 Issue；含业务密钥、生产数据或未授权连接的改动不会被接受。  
- LeadsHunter 等生产链路为私有仓；训练场与契约仓优先作为对外理解入口。  
- TACT / VECT 的 Phase 0 校验通过，不代表生产功能或生产连接已授权。

---

<p align="center">
  <sub>兰芯云朵 · LAN Cloud AI</sub><br/>
  <sup>以前，我们一起解决问题。现在，一起重新定义问题怎么解决。</sup>
</p>
