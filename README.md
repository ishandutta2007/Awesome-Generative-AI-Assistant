# Awesome-Generative-AI-Assistant

## Top Generative AI Assistant Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Enterprise Copilots, Agentic Assistants & Self-Hosted AI Platforms*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Generative AI Assistants**. These tools enable organizations to deploy AI-powered copilots and agentic assistants that understand enterprise context, automate workflows, answer employee and customer questions, and take action across connected systems—while maintaining governance, security, and data sovereignty.



**Examples** include ServiceNow Now Assist, Microsoft Copilot, Salesforce Agentforce, Glean, Moveworks, Aisera, Kore.ai, Forethought, Ada, and Yellow.ai (the category leaders).



**Open-source emphasis**: This section is expanded with active projects for self-hosted AI assistants, multi-model chat platforms, and agent orchestration frameworks—ideal for organizations building sovereign generative AI infrastructure without per-seat licensing or vendor lock-in.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[ServiceNow Now Assist](https://www.servicenow.com/)**  

  Enterprise GenAI suite on the Now Platform with skills for summarization, resolution notes, KB generation, and AI Agents for autonomous workflow execution; the Australia release adds Build Agent with MCP client integration (Figma, Linear, Prisma), semantic search for artifact discovery, and UI validation via Playwright . Now Assist is metered via "assists" with tiered consumption rates depending on skill or agent complexity .



- **[Microsoft Copilot](https://www.microsoft.com/en-us/microsoft-copilot)**  

  Microsoft 365-integrated AI assistant with Work IQ for organizational context across Outlook, Teams, SharePoint, and Dynamics 365; the expanded Copilot app introduces Cowork for delegated work, Code for app generation, and Autopilot (formerly Scout) as a cloud-hosted digital teammate; supports Claude and GPT models via routing .



- **[Salesforce Agentforce](https://www.salesforce.com/agentforce/)**  

  Agentic AI platform with job-ready agents (Casey for service, Paige for IT/HR, Hunter for sales, Fin for customer experience) that pursue goals over days and weeks; powered by Customer 360 context and Agent Script for deterministic + reasoning control; 7B+ Agentic Work Units delivered across deployments .



- **[Glean](https://www.glean.com/)**  

  Enterprise AI coworker and search platform connecting to apps and documents with permission-aware results; provides grounded answers with citations, people discovery, and work product drafting; available via browser, desktop, Slack, and MCP for supported AI tools .



- **[Moveworks (ServiceNow)](https://www.moveworks.com/)**  

  AI assistant platform and FedRAMP Moderate authorized GovCloud environment; serves as an AI front door for IT, HR, and Finance requests with reasoning engine for multi-step workflow automation; supports 100+ languages and ServiceNow native integration .



- **[Aisera](https://aisera.com/)**  

  Agentic AI platform for ITSM with multi-agent architecture (Universal Agent, Domain Agents, Task Agents) for autonomous incident detection, root cause analysis, CMDB correction, and change management; uses RLHF, ensemble decision methods, and confidence scoring .



- **[Kore.ai](https://kore.ai/)**  

  Agent platform Artemis edition with Agent Blueprint Language (ABL) for compiled, governed multi-agent systems; Dual-Brain Architecture combines agentic reasoning with deterministic flows; launches on Microsoft Azure with Foundry, Entra ID, and Teams integration .



- **[Forethought](https://forethought.ai/)**  

  Agentic customer support AI with Autoflows for voice and chat resolution; can access reservation systems, track orders, and take action without human handoff; channel-consistent across chat, email, and voice with multi-language support .



- **[Ada](https://www.ada.cx/)**  

  Agentic customer experience platform connecting to reservation, inventory, loyalty, and CRM systems for end-to-end issue resolution; AWS Travel and Hospitality Competency; supports 60 languages across Messaging, Voice, and Email .



- **[Yellow.ai](https://yellow.ai/)**  

  Agentic AI platform with Nexus EDGE desktop interface that perceives the live screen and executes local remediation (installing apps, resetting configs) rather than just suggesting fixes; cloud Nexus Agent for governed remediation, desktop EDGE for execution .



## Open-Source GitHub Projects



- **[LibreChat](https://github.com/danny-avila/LibreChat)**  

  Leading open-source AI chat platform (MIT, ~46k GitHub stars) unifying OpenAI, Anthropic, Google, Azure, AWS Bedrock, and local models in one interface; features no-code AI Agents with tools and file search, Code Interpreter (Python/Node/Go/Java/Rust), MCP support, Artifacts, web search, multimodal chat, and enterprise-ready SSO (OAuth, SAML, LDAP) with RBAC and rate limiting; Docker-deployable with MongoDB .



- **[Open WebUI](https://github.com/open-webui/open-webui)**  

  Extensible self-hosted AI platform (BSD-3 with branding clause) for teams; supports Ollama, OpenAI, Anthropic, and any OpenAI-compatible provider; features knowledge/RAG with 13 vector databases and hybrid search, model presets/agents with bound tools, channels for team collaboration, RBAC, SSO/OIDC/LDAP, SCIM 2.0, and Open Terminal for code execution .



- **[AnythingLLM](https://github.com/Mintplex-Labs/anything-llm)**  

  Open-source AI assistant with Desktop (single-user) and Docker (multi-user) editions; v1.13 introduces Model Router for hybrid local/cloud routing based on rules or LLM classification, Scheduled Jobs for automated agent runs with visual Cron Builder, and automatic memory extraction for personalization; supports any LLM and vector database .



- **[Dify](https://github.com/langgenius/dify)**  

  Open-source LLM application development platform with visual workflow builder, RAG pipeline, agents, and model management; supports Chatbot, Workflow, Chatflow, Agent, and Text Generator app types; Docker-deployable for building custom AI assistants with hundreds of model providers .



- **[RAGFlow](https://github.com/infiniflow/ragflow)**  

  Open-source RAG engine with vision-native DeepDoc parsing for complex PDFs, tables, and multi-column layouts; features template-based chunking, grounded citations with reduced hallucinations, agentic workflow and MCP support, and compatibility with heterogeneous data sources (Word, Excel, images, web pages); resource-intensive but high-fidelity for enterprise knowledge grounding .



- **[NEST Hub](https://github.com/contextzero/nest_hub)**  

  Self-hosted AI workforce platform with BYOK across 700+ models, organizational memory, multi-agent orchestration with mandatory review, and per-project RBAC with full audit trail; modules for MISSION CONTROL (routing/approvals), NEXUS (model layer), FORGE (code agents), OPERATOR (computer-use), and HIVE (persistent memory); Docker-deployable for air-gapped environments .



- **[WorkWit AI Agent](https://github.com/crane-in-clear-sky/WorkWit-AI-Agent)**  

  MIT-licensed self-hosted enterprise AI Agent platform for office automation; features contract review (risk points + revision suggestions), resume screening (match score + recommendation), Agent with auto-planning and sub-agent delegation, Skills Marketplace with sandboxed execution, scheduled automation, and multi-tenant RBAC; Docker Compose one-click deploy .



### Additional Strong Open-Source Options



- **LobeChat** — Open-source self-hosted AI chat with multi-provider support (OpenAI, Claude, Gemini, Ollama), persistent conversation history via PostgreSQL, voice input, plugins, and multi-assistant UI; deployable on Railway or Docker .

- **Cognita** — Open-source RAG framework for building modular AI assistants with customizable retrieval and generation pipelines.

- **Flowise** — Drag-and-drop LLM orchestration tool for building agents and assistants visually (note: feature development has slowed; code remains forkable).



**Frameworks for building custom systems**: Combine **LibreChat** for a unified multi-model chat interface with agents and MCP, **Open WebUI** for team collaboration with RAG and RBAC, **AnythingLLM** for hybrid local/cloud routing with scheduled automation, and **RAGFlow** for high-fidelity document grounding in a fully self-hosted generative AI assistant stack; layer **NEST Hub** for governed multi-agent orchestration with audit trails.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Generative AI assistants handling enterprise data must comply with applicable privacy regulations, data residency requirements, and organizational AI governance policies; permission-aware retrieval and audit logging are critical for production deployments.

- Self-hosted open-source solutions vary significantly in scope—LibreChat and Open WebUI provide broad chat and agent capabilities, while RAGFlow specializes in document grounding; full enterprise assistant deployments may require integration of multiple components and custom governance layers.

- Verify license terms for commercial use; LibreChat uses MIT, Open WebUI uses BSD-3 with branding clause, AnythingLLM is open-source (check repository), RAGFlow is open-source, and NEST Hub uses fair-code/source-available licensing .



---



**Made for CIOs, AI platform engineers, employee experience leaders, and customer support operations.**  

Let's make generative AI assistants more open, governed, and context-aware.
