# 兰芯云朵 · LAN Cloud AI

[English](./README.en.md) · [官网](https://lancloudtech.com)

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
| **[LeadsHunter](https://github.com/LAN-Cloud-AI/leadsHunter)** | 客户并没有沉默，他只是没在你的 CRM 里说话 | Mercury 生产 · Venus 三池 + 销售 APP 测试中 |
| **VECT** | 客户说「没事」，系统却看见他正在离开 | 飞书验证 → SaaS 筹备 |
| **[TACT](https://github.com/LAN-Cloud-AI/TACT)** | 车辆还没延误，系统已经看见延误会在哪里发生 | 飞书验证 → Phase 0 契约 / SaaS 启动 |
| **[云朵记账](https://github.com/LAN-Cloud-AI/LAN_Cloud_Internal_Expense)** | 订阅资产与报销不该再靠一张会漂的表 | 生产运行 |
| **兰芯裂变** | 商城成交之外，还要把转介绍做成可审计的动作 | 生产运行（小程序 / App） |
| **[艺匠市集](https://github.com/LAN-Cloud-AI/artist-marketplace)** | 独立艺术家也能跑通一套完整成交链路 | [公开演示](https://alien.lancloudtech.com) |

---

## 精选仓库

### 公域线索 · LeadsHunter

面向经销商销售团队的公域线索采集、AI 识别与交付系统：抖音 / 小红书等内容进池，Agent 判断意向。Mercury 按组织指派后走飞书 / 短链；Venus 改为三池结算，销售只在只读 APP 里接收投递与 10:00 摘要。

| 仓库 | 说明 | 可见性 |
| --- | --- | --- |
| [leadsHunter](https://github.com/LAN-Cloud-AI/leadsHunter) | Mercury 稳定生产；Venus 三池（归属 → 组织指派 → 账号分发）与移动 API | Private |
| [LH_evaluation_agent](https://github.com/LAN-Cloud-AI/LH_evaluation_agent) | 评论 / 帖子双管线评分 Agent（意向、摘要、证据、跟进建议） | Private |
| [LH_Training_Ground](https://github.com/LAN-Cloud-AI/LH_Training_Ground) | 场景（行业）+ 产品 SKU 的模型训练场；Skill 可同步回生产 | Public |
| [leadsHunter_APP](https://github.com/LAN-Cloud-AI/leadsHunter_APP) | Expo iOS/Android 销售端：首页 / 线索 / 通知、个推、10:00 摘要；Android beta 已发 | Private |

### 售后智能 · VECT × TACT

从飞书多维表格长出来的门店经营方法：VECT 经营客户关系，TACT 编排车间工单。共用六要素——**业务对象 · 状态 · 责任人 · 时点 · 证据 · 风险**。

| 仓库 | 说明 | 可见性 |
| --- | --- | --- |
| [TACT](https://github.com/LAN-Cloud-AI/TACT) | 多门店工单编排 Phase 0 契约：Schema、RuleSet、权限、事件不变量与合成验收 | Public |
| VECT（筹备中） | 客户生命周期精准管理：全功能档案、AI 质检、雷达预警、责任闭环 | — |

### 公司对外面

| 仓库 | 说明 | 可见性 |
| --- | --- | --- |
| [LAN_Web_Homepage](https://github.com/LAN-Cloud-AI/LAN_Web_Homepage) | 官网 lancloudtech.com（产品页 / 课程 / 企微名片） | Public |
| [LAN_Wechat_Official_miniProgram](https://github.com/LAN-Cloud-AI/LAN_Wechat_Official_miniProgram) | 官方微信小程序 | Private |
| [LAN_AI_Course_System](https://github.com/LAN-Cloud-AI/LAN_AI_Course_System) | AI 课程材料；公开课表见官网站内页 | Private |
| [lanxin-Fission-Frontend](https://github.com/LAN-Cloud-AI/lanxin-Fission-Frontend) | 裂变商城用户端（uni-app：小程序 / App） | Private |
| [lanxin-Fission-Backend](https://github.com/LAN-Cloud-AI/lanxin-Fission-Backend) | 裂变商城后端 | Private |
| [artist-marketplace](https://github.com/LAN-Cloud-AI/artist-marketplace) | 艺匠市集全栈示例：短信登录 / 定制商品 / 管理端 | Public |
| [LAN_Cloud_Internal_Expense](https://github.com/LAN-Cloud-AI/LAN_Cloud_Internal_Expense) | 订阅资产与报销：Cloudflare Workers / D1 / R2 + Access | Public |

---

## 我们相信什么

1. **AI 的第一份工作不是画图，是决定哪些数据值得相信。**  
2. **看见风险还不够，必须把动作送到正确岗位。**  
3. **自动化必须可解释、可审计；高风险动作保留人工与 Owner 确认。**  
4. **先在真实业务跑通，再用契约把门，再谈规模化开通。**

---

## 协作与边界

- 公开仓库欢迎阅读、讨论与 Issue；含业务密钥、生产数据或未授权连接的改动不会被接受。  
- LeadsHunter、裂变商城等生产链路为私有仓；训练场、契约仓与官网优先作为对外理解入口。  
- TACT / VECT 的 Phase 0 校验通过，不代表生产功能或生产连接已授权。  
- 私有仓链接对协作者以外的访客会 404，这是预期行为。

---

<p align="center">
  <sub>兰芯云朵 · LAN Cloud AI</sub><br/>
  <sup>以前，我们一起解决问题。现在，一起重新定义问题怎么解决。</sup>
</p>
