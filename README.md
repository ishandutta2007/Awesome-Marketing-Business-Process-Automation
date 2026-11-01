# Awesome-Marketing-Business-Process-Automation

## Top Marketing & Business Process Automation Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Visual Workflow Builders, Marketing Automation & Self-Hosted Orchestration Engines*  

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Marketing & Business Process Automation**. These tools enable organizations to automate repetitive marketing tasks, build behavior-triggered customer journeys, and connect disparate business systems—turning manual campaign execution into scalable, measurable workflows.



**Examples** include HubSpot Workflows, Zapier, Make, ActiveCampaign, Marketo, Workato, Tray.io, Microsoft Power Automate, Omnisend, and Customer.io (the category leaders).



**Open-source emphasis**: Marketing & Business Process Automation is a domain where open-source tooling is **genuinely mature and production-proven, but the right choice depends on whether you need marketing-specific automation or general workflow orchestration**. **Mautic** is the definitive open-source marketing automation platform—100% community-owned, free, and built for data sovereignty, with lead scoring, campaign builder, email marketing, and GDPR compliance . **Activepieces** provides the strongest MIT-licensed general workflow automation engine—500+ integrations, visual flow builder, AI agents, and human-in-the-loop steps . **n8n** offers a mature fair-code alternative with 350+ integrations and a node-based canvas, though its Sustainable Use License is not OSI-approved . The critical caveat: **no open-source project matches the integrated CRM + marketing + sales automation** of HubSpot Workflows  or the enterprise-scale agentic AI of Marketo —open-source tools excel at specific layers (marketing automation, workflow orchestration) and require assembly for full-stack automation.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[HubSpot Workflows](https://www.hubspot.com/)**  

  Native automation within HubSpot's platform; workflows can be built on contacts, companies, deals, tickets, quotes, and custom objects (Enterprise only) . Example use cases include creating deals when contacts submit quote requests, nurturing email flows triggered by form submissions, and updating lifecycle stages based on content interactions .



- **[Zapier](https://zapier.com/)**  

  Market-leading no-code automation platform with 7,000+ app integrations; trigger-and-action workflows for connecting SaaS tools without engineering effort.



- **[Make](https://www.make.com/)**  

  Visual automation platform with 3,000+ pre-built apps; Scenario Builder with If-Else, Merge, and iterators for complex data transformation.



- **[ActiveCampaign](https://www.activecampaign.com/)**  

  Marketing automation with behavior-triggered email sequences, AI-built workflows, and 1,000+ integrations . Features **AI-Suggested Actions** that recommend the next step based on contact behavior and engagement history, and automation triggers on site visits, purchases, form fills, and field changes .



- **[Adobe Marketo Engage](https://business.adobe.com/)**  

  Enterprise marketing automation with **agentic AI** embedded in workflows; AI agents help create campaigns, iterate on personalized copy and Firefly-powered images, and automate operational tasks like list imports and data normalization . Supports batch email, automated nurture, and advanced multi-step campaigns across email, web, mobile, chat, events, webinars, and digital advertising .



- **[Workato](https://www.workato.com/)**  

  Enterprise automation platform with AI-powered recipe building, low-code connectors, and comprehensive security compliance (PCI-DSS, ISO 27001, SOC 2, HIPAA).



- **[Tray.io](https://tray.ai/)**  

  Low-code automation platform with powerful data transformation capabilities; workspaces and custom connector builder for complex enterprise workflows.



- **[Microsoft Power Automate](https://powerautomate.microsoft.com/)**  

  Microsoft's automation platform with RPA capabilities, extensive connectors across Microsoft and third-party services, and deep integration with the Power Platform ecosystem.



- **[Omnisend](https://www.omnisend.com/)**  

  Ecommerce-focused email and SMS marketing automation; workflows triggered by store data, browsing behavior, and purchase history.



- **[Customer.io](https://customer.io/)**  

  Messaging automation platform with sophisticated trigger logic; automations can be triggered by attributes, segments, or events, with time-based conditions and delay controls for precise journey timing . Supports email, SMS, push, in-app messages, webhooks, and Slack messages .



## Open-Source GitHub Projects



### Marketing Automation Platforms (Mautic)



- **[Mautic](https://github.com/mautic/mautic)**  

  The **world's largest open-source marketing automation platform** (GPL-3.0, 100% community-owned with no commercial entity behind it) . Features: **lead scoring** with points, triggers, and groups; **stages** for tracking the marketing or sales funnel; **multichannel data collection** to fill customer profiles; **drag-and-drop campaign builder** for complex automation workflows; **email marketing** with A/B testing and multilingual support; **dynamic web content** personalization; and **GDPR compliance** tools for consent management, data reports, and erasure requests . **Self-hosting is unlimited** with no license costs, and the platform supports native integrations with HubSpot, Salesforce, Zoho CRM, and Microsoft Dynamics . **Best for organizations wanting a complete, self-hosted marketing automation platform** with full data sovereignty—but it requires infrastructure management and has a steeper learning curve than SaaS alternatives.



### General Workflow Automation (Activepieces, n8n)



- **[Activepieces](https://github.com/activepieces/activepieces)**  

  The **strongest MIT-licensed workflow automation alternative to Zapier and Make** . Features: **500+ pre-built pieces** (Google Sheets, Slack, OpenAI, HTTP, webhooks, and more); **visual flow builder** with branches, loops, and conditional logic; **AI Agents and AI Copilot** built into the flow builder; **human-in-the-loop approval steps**; **custom code steps** (JavaScript/TypeScript via Bun); **BullMQ-backed job queue** for reliable, retryable execution; **MCP server support** for AI tool integrations; and a **full REST API** . Deployable on Railway with one click (includes PostgreSQL and Redis) or Docker. **Key advantage over n8n**: MIT license (fully permissive for commercial use) and **unlimited task execution on paid plans** . **Best for teams wanting a permissive-licensed, self-hostable automation platform** with AI capabilities—but it has fewer integrations than Zapier (500+ vs 7,000+).



- **[n8n](https://github.com/n8n-io/n8n)**  

  A mature open-source **node-based workflow automation tool** (Sustainable Use License, not OSI-approved) . Features: **350+ integrations** (growing); **visual canvas** with drag-and-drop nodes for connecting services; **logic and branching** with conditions, loops, and decision-making; **self-hosting** on your own servers for data privacy; and **custom nodes** for unlimited extensibility . **Key advantage**: lower long-term cost when self-hosted (no per-task fees), and sensitive data stays on your infrastructure . **Best for teams wanting a mature, widely-adopted automation platform** with a large community—but the Sustainable Use License has restrictions on resale and is not OSI-approved.



### Additional Strong Open-Source Options



- **MessageBirds** — Open-source, event-driven **Customer Data & Engagement Platform** (Apache-2.0) with a Python client SDK covering the core send-an-event / read-a-profile loop . **Early-stage** (v0.1.0)—for developers wanting to build custom CDP pipelines rather than a turnkey marketing automation platform.



**Frameworks for building custom systems**: For **complete marketing automation with lead scoring and campaigns**, Mautic is the only mature open-source option . For **general workflow orchestration with MIT licensing and AI agents**, Activepieces . For **mature node-based automation with data privacy**, n8n (accepting the Sustainable Use License) . **No open-source project matches the integrated CRM + marketing + sales automation** of HubSpot Workflows  or the enterprise-scale agentic AI of Marketo —choose based on whether you need marketing-specific automation (Mautic) or general workflow orchestration (Activepieces, n8n).



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Marketing automation platforms handling customer data must comply with applicable privacy regulations (GDPR, CCPA, CAN-SPAM) and implement proper consent mechanisms; **self-hosted solutions place full responsibility for security patches, backups, and data governance on the operator**.

- **Open-source marketing automation is mature for core campaign workflows**—Mautic provides lead scoring, campaigns, email marketing, and GDPR tools , and Activepieces provides general workflow automation with MIT licensing . However, **no open-source project matches the integrated CRM + marketing + sales automation** of HubSpot  or the enterprise-scale agentic AI of Marketo —organizations requiring that depth should evaluate commercial platforms or plan for integration.

- Verify license terms for commercial use; Mautic uses GPL-3.0 , Activepieces uses MIT , and n8n uses the Sustainable Use License (not OSI-approved, with resale restrictions) .



---



**Made for marketing operations teams, growth leaders, and organizations choosing their automation stack.**  

Let's make marketing and business process automation more open, but with clear eyes about the integrated CRM and enterprise AI gaps that commercial platforms still fill.
