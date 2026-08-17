# LAN Cloud AI · 兰芯云朵

[中文](./README.md) · [Website](https://lancloudtech.com)

**Redefining how automotive retail and aftersales are operated — with AI.**

We turn *See → Understand → Orchestrate → Judge* into shippable product capabilities: discover opportunity in public signals, surface risk in customer relationships, anticipate delay on the shop floor — then route the next action to the right person.

> **Method:** Business rules × multidimensional tables / event systems × AI  
> **Path:** Prove in real stores, then SaaS-ify behind contracts.

---

## Capability Map

```text
Create · AIGC
   ↓
See · LeadsHunter           Public content → business signals → actionable leads
Understand · VECT           Fragmented data → relationship temperature → risk & accountable actions
Orchestrate · TACT          Work orders → trusted state → explainable dispatch & timing alerts
Judge · AI Analyst / Agent  Trusted samples → counter-intuitive insights → layered actions
```

| Product | One-liner | Status |
| --- | --- | --- |
| **[LeadsHunter](https://github.com/LAN-Cloud-AI/leadsHunter)** | Customers aren’t silent — they just aren’t speaking inside your CRM. | In production (Mercury) |
| **VECT** | They say “it’s fine” — the system sees they’re leaving. | Feishu-proven → SaaS prep |
| **[TACT](https://github.com/LAN-Cloud-AI/TACT)** | The car isn’t late yet — the system already sees where delay will form. | Feishu-proven → Phase 0 contracts / SaaS underway |
| **[Cloud Ledger](https://github.com/LAN-Cloud-AI/LAN_Cloud_Internal_Expense)** | Subscriptions and reimbursements should not live on a drifting spreadsheet. | In production |
| **Lanxin Fission** | Commerce plus auditable referral actions | In production (mini program / App) |
| **[Artist Marketplace](https://github.com/LAN-Cloud-AI/artist-marketplace)** | A complete checkout path for independent artists | [Public demo](https://alien.lancloudtech.com) |

---

## Featured Repositories

### Public Leads · LeadsHunter

Public-domain lead capture, AI scoring, and delivery for dealer sales teams: ingest Douyin / Xiaohongshu content, score intent with an Agent, then assign by organization and deliver via Feishu cards and short links.

| Repo | Description | Visibility |
| --- | --- | --- |
| [leadsHunter](https://github.com/LAN-Cloud-AI/leadsHunter) | Ingestion, job engine, multi-tenant RBAC, lead pool & delivery (Mercury) | Private |
| [LH_evaluation_agent](https://github.com/LAN-Cloud-AI/LH_evaluation_agent) | Comment & post dual-pipeline scoring Agent | Private |
| [LH_Training_Ground](https://github.com/LAN-Cloud-AI/LH_Training_Ground) | Scenario (industry) + product SKU training ground; skills sync to production | Public |
| [leadsHunter_APP](https://github.com/LAN-Cloud-AI/leadsHunter_APP) | Expo mobile app: leads, push, and deep links | Private |

### Aftersales Intelligence · VECT × TACT

Born from Feishu multidimensional tables: VECT runs customer relationships; TACT orchestrates workshop work orders. Shared six pillars — **object · state · owner · timing · evidence · risk**.

| Repo | Description | Visibility |
| --- | --- | --- |
| [TACT](https://github.com/LAN-Cloud-AI/TACT) | Multi-store work-order orchestration Phase 0 contracts: schemas, RuleSets, permissions, event invariants, synthetic acceptance | Public |
| VECT (in prep) | Customer lifecycle precision management: full profiles, AI QC, radar alerts, accountable closed loops | — |

### Company Surface

| Repo | Description | Visibility |
| --- | --- | --- |
| [LAN_Web_Homepage](https://github.com/LAN-Cloud-AI/LAN_Web_Homepage) | Official site lancloudtech.com (products / courses / WeCom card) | Public |
| [LAN_Wechat_Official_miniProgram](https://github.com/LAN-Cloud-AI/LAN_Wechat_Official_miniProgram) | Official WeChat mini program | Private |
| [LAN_AI_Course_System](https://github.com/LAN-Cloud-AI/LAN_AI_Course_System) | AI course materials; public syllabus lives on the site | Private |
| [lanxin-Fission-Frontend](https://github.com/LAN-Cloud-AI/lanxin-Fission-Frontend) | Fission mall client (uni-app: mini program / App) | Private |
| [lanxin-Fission-Backend](https://github.com/LAN-Cloud-AI/lanxin-Fission-Backend) | Fission mall backend | Private |
| [artist-marketplace](https://github.com/LAN-Cloud-AI/artist-marketplace) | Artist shop example: SMS login / custom SKUs / admin | Public |
| [LAN_Cloud_Internal_Expense](https://github.com/LAN-Cloud-AI/LAN_Cloud_Internal_Expense) | Subscriptions & reimbursements on Cloudflare Workers / D1 / R2 + Access | Public |

---

## What We Believe

1. **AI’s first job isn’t charting — it’s deciding which data deserves trust.**  
2. **Seeing risk isn’t enough — the action must reach the right role.**  
3. **Automation must be explainable and auditable; high-risk actions stay human- and owner-gated.**  
4. **Prove in real operations, lock the gates with contracts, then scale SaaS access.**

---

## Collaboration & Boundaries

- Public repos welcome reading, discussion, and Issues. Changes involving business secrets, production data, or unauthorized connectivity will not be accepted.  
- Production paths such as LeadsHunter and Fission are private; training grounds, contract kits, and the website are the preferred public entry points.  
- Passing Phase 0 checks for TACT / VECT does not authorize production features or production connectivity.  
- Private repo links 404 for visitors who are not collaborators. That is expected.

---

<p align="center">
  <sub>LAN Cloud AI · 兰芯云朵</sub><br/>
  <sup>We used to solve problems together. Now we redefine how problems get solved.</sup>
</p>
