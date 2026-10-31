# Awesome-Conversational-Support-ITSM

# Awesome-Conversational-Support-ITSM

**Top Conversational Support ITSM (Opensource) 🌟 Star if you like it! 🌟**



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on AI Service Desk, Slack-First Ticketing, Agent Assist & Self-Hosted Helpdesk Automation*

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Conversational Support & ITSM**. These tools enable employees and customers to resolve issues through chat, Slack, or messaging interfaces—with AI agents handling routine requests and escalating to humans when needed—from fully managed enterprise platforms with agentic resolution to self-hosted frameworks that give organizations control over their service desk data and LLM provider.



**Examples** include Atlassian Assist, Zendesk AI, Intercom, Moveworks, Aisera, Freshservice, Capacity, Forethought, Ada, and Yellow.ai (the category leaders in commercial space).



**Open-source emphasis**: This section is expanded with every relevant project for self-hosted conversational support, RAG-based IT agents, and open helpdesk infrastructure. **Critical note**: True open-source conversational ITSM is nascent—**helpdesk-agentico** is the only purpose-built RAG agent for IT support with human-in-the-loop approval , while **Chatwoot** provides the support inbox foundation without native ITSM workflows . No open-source project matches Moveworks' multi-system agentic execution or Aisera's enterprise service desk depth, but for teams building conversational support from scratch, the foundational components exist.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global conversational AI and IT support automation market is estimated at **$14B–$19B** and projected to surpass **$75B–$115B+** by the mid-2030s, expanding at a robust **21%–25%+ CAGR**.

The sector features a **hybrid competitive structure**: heavily **concentrated** at the core enterprise platform layer (dominated by hyperscalers and large ITSM incumbents like ServiceNow, Atlassian, and Zendesk), but **moderately fragmented** at the application and point-solution layer where niche agentic vendors and composable open-source frameworks compete to solve specialized, cross-system workflows.

## SaaS/Hosted Platforms

| Company / Product | Company Size (Valuation / Revenue) | Starting Tier Pricing | Free Tier / Trial Limits | Key Features & Best For | Trade-offs |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[Atlassian Assist](https://www.atlassian.com/software/jira/service-management)** (JSM) | **$53B market cap** (~$5.22B FY25 revenue) | **$20/agent/month** (Standard) or **$51.42/agent/month** (Premium) billed annually | **Free for up to 3 agents** permanently with 2 GB storage; includes core incident request queues and unlimited portal customers (AI Assist features require Premium tier). | Slack-native service management for Jira Service Management. Employees react with `:ticket:` or `/assist` in Slack to create tickets; works across service spaces without full Jira licenses. | AI virtual agent requires Premium+ ($51.42+/mo); single Slack workspace per Jira site; no native two-way thread sync. |
| **[Zendesk AI](https://www.zendesk.com/)** | **$10.2B valuation** (Acquired by H&F/Permira; ~$1.34B+ ARR) | **$19/agent/month** billed annually (Support Team) or **$55/agent/month** (Suite Team) | **14-day free trial** with full access to Suite Professional features (no permanent free tier). | Built-in AI agents and agent assist within Zendesk Suite. Best for organizations wanting resolution-oriented automation natively inside their ticketing tool. | Outcome-based AI pricing ($1.50–$2.00 per automated resolution); Copilot is an additional $50/agent/mo; per-seat + per-resolution fees stack up. |
| **[Freshservice](https://www.freshworks.com/freshservice/)** | **$3.8B market cap** (~$839M FY25 revenue) | **$19/agent/month** billed annually (Starter) or **$49/agent/month** (Growth) | **21-day free trial** with full Enterprise-tier features (no permanent free tier). | Structured ITSM platform with incident management, asset tracking, and Freddy AI service desk automation. Best for mid-market IT teams. | Freddy AI sessions require a separate add-on (~$29–$35/agent/mo); managed assets are capped at 100 on the Growth tier. |
| **[Intercom](https://www.intercom.com/)** | **$3.6B acquisition valuation** (Salesforce; ~$400M ARR) | **$29/seat/month** billed annually (Essential) | **14-day free trial** (expandable by 7 days upon request) with full platform features, Fin AI Agent, and Copilot; no credit card required. | AI-first conversational platform with Fin AI Agent and modern helpdesk. Best for teams wanting integrated customer support with AI automation. | Outcome-based billing charges $0.99 per resolved conversation on top of seat licenses; advanced capabilities require higher tiers. |
| **[Moveworks](https://www.moveworks.com/)** | **$2.85B acquisition valuation** (ServiceNow; ~$100M+ ARR) | **$150/user/year** (AWS Marketplace entry for 1,000–2,500 employees; ~$150K/year baseline contract) | **No self-serve free tier or public trial**; proof of concepts (POCs) and sandbox pilots are sales-negotiated for enterprise scoping. | Autonomous agentic AI for enterprise employee support across IT, HR, and finance with deep action resolution via Slack/Teams. | High enterprise entry barrier (six-figure annual minimum commitment); being integrated into ServiceNow enterprise packaging. |
| **[Aisera](https://aisera.com/)** | **~$257M ARR** (Acquired by Automation Anywhere; $150M+ raised) | **$200,000/year** (AWS Marketplace entry tier for up to 1,000 users; ~$108K/yr median contract) | **30-day trial for up to 50 users** via AWS Marketplace private listing (no self-serve free plan). | Deep IT and HR service desk domain configuration with multi-LLM orchestration. | Heavy implementation setup fees (often 50%–100% of Year-1 license); post-acquisition roadmap changes. |
| **[Ada](https://www.ada.cx/)** | **$1.2B valuation** (~$70M+ ARR) | **$33,000/year** (AWS Marketplace entry tier for 60,000 conversations; ~$60K/yr typical starting plan) | **No self-serve free plan or public trial**; guided proof of concept (PoC) available only via enterprise sales qualification. | Agentic customer experience platform with deep workflow actions and reasoning engines across omnichannel support. | High annual entry price; requires sales consultation and substantial implementation commitment ($15K–$100K+). |
| **[Yellow.ai](https://yellow.ai/)** | **$550M valuation** (Public listing via SPAC / $350M+ raised) | **$0/month** (Free tier) or **Custom enterprise quotes** for scaled dynamic AI | **Free forever plan** includes 5,000 monthly bot sessions, 500 chat/email tickets/month, unlimited agent seats, 2 channels, and 1,000 WhatsApp conversations/mo. | Omnichannel enterprise conversational AI supporting both customer engagement and internal employee IT desks. | Freemium tier excludes advanced analytics, Doc Cog, Voice, and SMS channels. |
| **[Capacity](https://www.capacity.com/)** | **$100M+ ARR** ($159M+ venture funding raised) | **$25,000/year** (~$2,083/month baseline annual platform fee for Core tier) | **No public free tier or self-serve trial**; custom guided proof-of-concept (POC) sandbox environments provided after sales scoping. | AI support platform combining helpdesk ticketing, knowledge automation, and agent assist without separate LLM token bills. | Platform fee plus volume-based AI usage fees require careful capacity and cost modeling; no instant onboarding. |
| **[Forethought](https://forethought.ai/)** | **Acquired by Zendesk** ($115M+ raised; Zendesk's largest acquisition) | **$50/agent/month** (Assist) + **$0.50–$2.00/conversation** (Solve) | **No self-serve trial or free tier**; enterprise Proof of Value (POV) simulations run against historical ticket datasets. | Agentic AI workflow suite (Solve, Triage, Assist) purpose-built for ticket routing, agent assistance, and autonomous resolution. | Requires high historical volume (20,000+ tickets); implementation packages range from $10,000–$50,000+. |

## Open-Source GitHub Projects



- **[helpdesk-agentico](https://github.com/dfserver1/helpdesk-agentico)**

  **Open-source RAG support agent for IT with self-learning memory** (license per repo) — **the only purpose-built open-source conversational ITSM agent** found in this research . **Features**: **RAG-based IT support agent** with **Gemini (free tier)**; **self-training memory** (`MemoryIngest`/`MemoryRecall` endpoints)—teach the agent from past resolutions; **human-in-the-loop (HITL)**—agent creates draft tickets requiring `ChatDecide` approval before finalization; **SLA calculation** on ticket creation; **SharePoint/Teams/Outlook/web connectors** via `ConnectorsSearch`; **JWT authentication** (60-min expiry, configurable); FastAPI + Streamlit stack . **Tech stack**: Python (FastAPI), Streamlit, Gemini API. **Deploy**: Self-hosted (Hugging Face Spaces demo available) . **Trade-off**: **Early-stage project**—Spanish-language documentation; no traditional helpdesk UI (inbox, queues, reporting); Gemini dependency for free tier. **Best for**: developers wanting a working RAG agent with self-learning memory and HITL approval for IT support—especially those wanting to build on a functional foundation rather than starting from scratch.



- **[Chatwoot](https://github.com/chatwoot/chatwoot)**

  **Open-source customer engagement platform** (MIT for Community Edition) — **the support inbox foundation** for conversational support, with live chat, email, and social channels . **Features**: Shared inbox; website live chat widget; email and social channel support; **human handoff from bots**; multi-brand support. **Enterprise Edition** adds custom dashboards, SLA management, agent scheduling, and IP blocking. **Tech stack**: Ruby on Rails, Vue.js. **Deploy**: Self-hosted or Chatwoot Cloud. **Trade-off**: **No native ITSM workflows**—no incident/problem/change management, no asset CMDB, no service catalog. AI integration is via webhooks to external services. **Best for**: teams wanting a self-hosted support inbox with live chat and bot handoff—pair with an external ITSM tool or custom ticketing logic.



### Additional Strong Open-Source Options



- **osTicket** — Widely-used open-source support ticket system (GPL). **Note**: **Traditional ticketing, not conversational AI**—no chat interface, no RAG agent, no Slack integration. **Best for**: organizations needing basic self-hosted ticketing without AI, not conversational ITSM.

- **Zammad** — Open-source helpdesk with email, chat, and social channels (AGPL). **Note**: Helpdesk foundation; AI features require integrations. **Best for**: teams wanting a mature open-source helpdesk without conversational AI built in.

- **Rasa** — Open-source conversational AI framework (Apache-2.0). **Note**: **NLU framework, not ITSM**—no ticketing, no SLA, no service catalog. **Best for**: building custom conversational flows that feed into a separate ticketing system.



**Frameworks for building custom systems**: Combine **helpdesk-agentico** for RAG-based IT resolution with HITL approval, **Chatwoot** for the support inbox and channel management, and **Rasa** for custom NLU flows—creating a composable open-source conversational ITSM stack. **None of these match Moveworks' multi-system agentic execution or Aisera's enterprise service desk depth**, but for teams prioritizing data sovereignty, the foundational components exist.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Conversational support and ITSM platforms handling employee and customer data must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls for service desk tickets and conversations.

- **The "Slack-first ticketing" vs. "AI service desk" vs. "agentic execution" vs. "support inbox" distinction is critical.** **Atlassian Assist** is **Slack-first ticketing**—it creates Jira tickets from Slack, but AI requires Premium+ . **Zendesk AI, Intercom, Freshservice, and Yellow.ai** are **AI-enhanced support platforms**—they add AI to existing helpdesk/ITSM . **Moveworks and Aisera** are **agentic AI service desks**—they execute multi-step requests across enterprise systems . **Capacity and Forethought** are **AI resolution platforms**—they automate specific support workflows . **Ada** is **agentic customer experience**—deep integrations for resolution . **helpdesk-agentico** is a **RAG IT agent**—it resolves from knowledge and creates draft tickets with approval . **Chatwoot** is a **support inbox**—the channel layer without ITSM workflows . **Choose based on whether you need ticketing, AI resolution, agentic execution, or inbox foundation.**

- **Moveworks and Aisera are enterprise-only with six-figure floors.** Moveworks anchors at **$150/user/year** (~$150K for 1,000 employees) with **no free trial** . Aisera median is **~$108K/year** with **implementation adding 50–100%** . **Neither is viable for small teams**—evaluate only if you are prepared for enterprise procurement.

- **Zendesk and Intercom both stack AI costs on top of seat pricing.** Zendesk: **$115/seat + $1.50–$2.00/resolution + $50 Copilot add-on** . Intercom: **$29/seat + outcome-based Fin fees** . **Model your resolution volume before committing**—AI costs can exceed seat costs at scale.

- **Yellow.ai is the only platform with a genuine free-forever tier**—**5,000 bot conversations, 500 tickets, unlimited agents, 2 channels** . **For teams evaluating conversational AI without a sales call, it is the pragmatic starting point.**

- **Atlassian Assist is no longer a standalone purchase.** It is tied to Jira Service Management Cloud, with AI features on **Premium+ tiers** . **JSM Free covers 3 agents** but not Assist AI . **Do not plan an Assist deployment on JSM Free.**

- **helpdesk-agentico is the only open-source conversational ITSM agent**, but it is **early-stage with Spanish documentation and no traditional helpdesk UI** . **The trade-off**: it provides RAG resolution and HITL ticket drafting, not a complete service desk. **For teams wanting to build conversational ITSM from scratch, it is the functional starting point.**

- **Chatwoot is not an ITSM tool.** It provides the support inbox and channels but **lacks incident, problem, change, SLA, and CMDB capabilities** . **Pair it with an external ITSM tool or custom ticketing logic for full service management.**

- **Pricing opacity is near-universal.** Atlassian (Premium+), Zendesk (Enterprise), Intercom (Advanced), Moveworks, Aisera, Freshservice (Enterprise), Capacity, Forethought, Ada, and Yellow.ai (Premium) all require sales contact or tier commitment. **Validate with direct vendor conversations against your ticket volume and AI resolution targets.**

- Self-hosted open-source solutions require proper infrastructure (Gemini API for helpdesk-agentico, Ruby/PostgreSQL for Chatwoot), security hardening for service desk credentials, and ongoing maintenance. **Conversational support systems handle employee and customer PII**—ensure your deployment meets your organization's privacy and compliance requirements before connecting production channels.



---



**Made for IT service managers, support teams, and organizations building transparent conversational ITSM solutions.**

Let's make Conversational Support & ITSM more open, data-driven, and resolution-friendly.
