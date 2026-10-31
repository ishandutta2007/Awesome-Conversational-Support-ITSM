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

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Atlassian Assist](https://www.atlassian.com/software/jira/service-management)** (Jira Service Management)

  **Slack-native service management** for Jira Service Management. Employees react with `:ticket:` or `/assist` in Slack to create tickets; Assist works with service spaces and can be used by people without Jira licenses . **Pricing**: **Tied to Jira Service Management Cloud**; AI-powered virtual service agent positioned on **Premium and Enterprise tiers**—**Assist is no longer available as a standalone purchase for new customers** . Jira Service Management is **free for up to 3 agents** . **Free tier**: Yes, 3 agents on JSM Free; Assist AI requires Premium+. **Best for**: Atlassian-centric organizations wanting Slack-first ticketing without leaving the Jira ecosystem—**trade-off**: Assist only in Premium+; single Slack workspace per Jira site; no native two-way thread sync .



- **[Zendesk AI](https://www.zendesk.com/)**

  **AI agents and agent assist** within Zendesk Suite. **Outcome-based pricing**: AI agents bill **per automated resolution** beyond included allowance (~**$1.50–$2.00 per resolution**); **Copilot is a separate $50/agent/month add-on** . **Pricing**: **Support Team $19/agent/mo annually**; **Suite Team $55**; **Suite Professional $115**; Suite Enterprise quote-only. AI resolution fees stack on top of seat costs. **Free tier**: **No permanent free tier**—**14-day free trial** on Suite Professional features . **Best for**: teams wanting AI resolution with per-outcome billing—**trade-off**: per-seat plus per-resolution stacks; resolution definition is vendor-determined.



- **[Intercom](https://www.intercom.com/)**

  **AI-first support platform** with Fin AI Agent and helpdesk. **Pricing**: **Essential from $29/seat/month annually** (includes Fin AI Agent and full helpdesk); Fin usage measured in **outcomes** (resolution, procedure handoff, qualification)—one outcome per conversation, no charge for escalations . **Free tier**: **14-day free trial** with full plan features plus free Fin, Copilot, and Proactive Support Plus; **no credit card required**; self-serve extension of **7 days** available from day 13 for eligible trials . **Best for**: teams wanting AI agent plus helpdesk in one platform with outcome-based AI billing—**trade-off**: seat pricing plus outcome fees; advanced add-ons extra.



- **[Moveworks](https://www.moveworks.com/)** (**Acquired by ServiceNow**)

  **Agentic AI for employee support** across IT, HR, and finance. **Pricing**: **Quote-only, per-employee** (not per-agent)—**no public tiers, no self-serve, annual only**. **AWS Marketplace anchor: $150/user/year for 1,000–2,500 users** (~$150,000/year for 1,000 employees) . **Median buyer pays ~$130,000/year** (range ~$89,500–$271,333) . **Free tier**: **None—no free trial, no self-serve** . **Best for**: large enterprises wanting multi-system agentic execution (password reset, access provisioning) via Slack/Teams—**trade-off**: six-figure minimum; now being folded into ServiceNow bundles.



- **[Aisera](https://aisera.com/)** (**Acquired by Automation Anywhere**)

  **AI service desk** for IT, HR, and customer support. **Pricing**: **Quote-only across 11 plans**—pricing page 404s; **median buyer pays ~$108,225/year** (Vendr data, range ~$53K–$118K); **AI Service Desk marketplace tiers $200K/year up to 1,000 users, $1.2M/year up to 10,000 users** . **Free tier**: **None published**—**30-day trial up to 50 users via AWS Marketplace** . Implementation adds **50–100% of Year-1 license** . **Best for**: enterprises wanting deep ITSM domain configuration—**trade-off**: post-acquisition roadmap uncertainty; heavy implementation services.



- **[Freshservice](https://www.freshworks.com/freshservice/)**

  **ITSM platform** with Freddy AI. **Pricing**: **Starter $19/agent/mo annually** (incident management, knowledge base, self-service portal); **Growth $49** (asset management, service catalog, approvals—capped at 100 managed assets); **Pro $99** (problem, change, project management); **Enterprise quote-only** (Freddy AI, orchestration, sandbox) . **Freddy AI sessions are a separate add-on, ~$29–$35/agent/month** . **Free tier**: **21-day free trial** with Enterprise-level features; no permanent free tier . **Best for**: mid-market IT teams wanting structured ITSM with optional AI—**trade-off**: Freddy AI costs extra; asset cap on Growth.



- **[Capacity](https://www.capacity.com/)**

  **AI-powered support platform** with helpdesk, live chat, and agent assist. **Pricing**: **Platform fee (annual subscription) plus usage-based AI Agent pricing**; LLM token costs included in usage—no separate token bill. Three tiers: **Core** (knowledge base, helpdesk, AI Agent Builder, 100 AI Assistant questions, 100GB storage); **Pro** (adds live chat, Agent Assist, conversation intelligence, 1TB); **Enterprise** (HIPAA, campaigns/CRM, 2TB) . **Free tier**: **None listed** . **Best for**: teams wanting transparent AI usage pricing without token surprises—**trade-off**: platform fee plus usage requires volume modeling.



- **[Forethought](https://forethought.ai/)**

  **Agentic AI for customer support** with Solve (resolution), Assist (agent productivity), and Triage. **Pricing**: **Quote-only, no published prices**—requires **20,000+ historical tickets** before selling; **Solve per-conversation ~$0.50–$2.00**; **Assist per-agent ~$50–$150/month**; **Voice AI ~$0.10–$0.50/minute** . **Free tier**: **None—no free trial** . Implementation **$10,000–$50,000+** . **Best for**: teams with substantial ticket volume wanting resolution automation—**trade-off**: high volume prerequisite; no self-serve evaluation.



- **[Ada](https://www.ada.cx/)**

  **Agentic customer experience** platform with action-taking AI agents. **Pricing**: **Quote-only; no published rates**—**AWS Marketplace entry: $33,000/year for 60,000 conversations**; Capterra/GetApp list **starting at $60,000 annually** . **Free tier**: **No free plan, no free trial** . Implementation **$15,000–$100,000+** . **Best for**: enterprises wanting deep system integrations for end-to-end resolution—**trade-off**: high entry price; consultation-only sales process.



- **[Yellow.ai](https://yellow.ai/)**

  **Conversational AI platform** for customer and employee support. **Pricing**: **Freemium plan** includes **5,000 monthly bot conversations**, **500 chat/email tickets/month**, **unlimited agent seats**, **2 channels**, FAQ module . **Premium**: custom quote. **Free tier**: **Yes—Freemium plan** with limits above; **1,000 free WhatsApp conversations/month** . **Best for**: teams wanting a genuine free tier to evaluate conversational AI—**trade-off**: freemium lacks Doc Cog, Data Explorer, SMS, and Voice.



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
