# Awesome-LLM-Frameworks

### Top LLM Frameworks Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Composable Orchestration, Agent Development & Production LLM Applications*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **LLM Frameworks**. These tools provide abstractions for prompts, chains, agents, tools, memory, and retrieval — enabling developers to build everything from simple RAG pipelines to complex multi-agent systems with composable building blocks.



**Examples** include Voiceflow, Botpress, Microsoft Copilot Studio, LangChain, Flowise, Retool, Stack AI, Dialogflow, Cognigy, and Kore.ai (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom agent development, and transparent orchestration — ideal for AI engineers, product builders, and teams building vendor-neutral LLM applications.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

All prices in USD, verified October 2026 (annual billing noted where it applies).

| Platform | Description | Starting Price | Free Tier / Trial |
|---|---|---|---|
| **[Voiceflow](https://www.voiceflow.com/)** | Collaborative conversational AI design platform with visual flow builder for voice and chat agents; popular for prototyping and team-based agent design. | **Pro: $60/month** for the first editor (includes 10,000 credits/month) | **Free Sandbox**: 1 editor, 2 agents, **100 one-time credits** (credits do not renew monthly) |
| **[Botpress](https://botpress.com/)** | Conversational AI platform with visual flow builder, built-in NLU, knowledge bases, and multi-channel deployment; open-source core with hosted cloud option. | **Plus: $150/month** (billed annually; 250 conversations included, extra packs $65 per 100 conversations) | **Free plan**: **100 conversations/month**, 3 seats, 3 agents, 1,000 table rows, 100 MB vector + 100 MB file storage |
| **[Microsoft Copilot Studio](https://www.microsoft.com/en-us/microsoft-copilot/microsoft-copilot-studio)** | Low-code platform for building custom copilots integrated with Power Platform and Microsoft 365; strong enterprise adoption (55% user adoption per G2). | **Pay-as-you-go: $0.01 per Copilot Credit**; prepaid capacity pack **$200/month for 25,000 credits** | **30-day free trial environment**: create agents and test in the chat panel, publishing not included (extendable once by 30 days) |
| **[Flowise](https://flowiseai.com/)** | Open-source drag-and-drop UI for building LLM flows and AI agents built on LangChain components; self-hostable with cloud offering. | **Cloud Starter: $35/month** | **Free cloud tier**: **2 flows, 2 assistants, 100 predictions/month, 5 MB storage** |
| **[Retool](https://retool.com/)** | Low-code platform for building internal tools and workflows with AI capabilities; Windmill serves as the leading open-source alternative. | **Team: $10/builder/month** + **$5/internal user/month** (billed annually) | **Free plan**: up to **5 users**, 250 pooled AI credits/month, 500 workflow runs/month, ~20 agent-hours/month, 5 GB stored data |
| **[Stack AI](https://www.stack-ai.com/)** | No-code platform for building AI workflows and applications with visual drag-and-drop interface for RAG pipelines, chatbots, and document processing. | **AWS Marketplace "StackAI Hosted": $120,000/year** (12-month contract, up to 5,000 runs/month); Enterprise otherwise custom-quoted | **Free plan**: **500 runs/month**, 2 projects, 1 seat (community support on Discord) |
| **[Dialogflow (Google)](https://cloud.google.com/dialogflow)** | Google's conversational AI platform for building chatbots and voice assistants with visual intent/entity editor; strong for Google Cloud deployments. | **CX: $0.007/text request** ($0.06/minute audio); **ES Essentials: $0.002/text request** | **ES Trial Edition**: free text requests capped at **180 requests/minute** (audio 1,000/day, 15,000/month); **CX: $600 trial credit valid 12 months** |
| **[Cognigy](https://www.cognigy.com/)** | Enterprise conversational AI platform (now part of NiCE) with visual flow editor for voice and chat automation; used by large contact centers. | **Per-conversation billing**: AWS Marketplace bundle **$43,080/year per 60,000 conversations** (~$0.72/conversation; one conversation = 50 user inputs within 24 h) | **30-day free trial** at trial.cognigy.ai (full flow editor and NLP in a sandbox environment) |
| **[Kore.ai](https://kore.ai/)** | Enterprise virtual assistant platform with Bot Builder for NLP-enabled bots; 43% user adoption and 7-month payback period per G2. | **AWS Marketplace "AI for Service": $80,000/year platform fee + $0.20 per session** | **Free trial with $500 starting credit** (20 requests/minute; includes Conversation Designer, Dialog Builder, Knowledge Graph, Multi-Engine NLP) |



## Open-Source GitHub Projects



- **[LangChain](https://github.com/langchain-ai/langchain)**  

  **The most popular general-purpose LLM framework** — provides abstractions for prompts, chains, agents, tools, memory, and 700+ integrations. Best for rapid prototyping and teams new to LLM development. Note: abstraction overhead and historical breaking changes are common challenges .



- **[LangGraph](https://github.com/langchain-ai/langgraph)**  

  Graph-based agent orchestration from LangChain — requires explicit edge definition but provides powerful state management and checkpointing for complex multi-agent workflows. The recommended choice when agent state persistence matters .



- **[LlamaIndex](https://github.com/run-llama/llama_index)**  

  **Data-centric framework focused on RAG** — excels at document ingestion, indexing, and retrieval. Shines when the primary use case is connecting LLMs to data with complex document processing. Often used alongside LangChain for agent orchestration .



- **[Haystack](https://github.com/deepset-ai/haystack)**  

  **Production-ready orchestration framework** with 25k+ stars — modular pipelines and agent workflows with explicit control over retrieval, routing, memory, and generation. Built for scalable agents, RAG, multimodal applications, and semantic search .



- **[Semantic Kernel](https://github.com/microsoft/semantic-kernel)**  

  **Microsoft's enterprise AI orchestration SDK** — native C#, Python, and Java support with Azure integration, planners for automatic function orchestration, and semantic memory. Ideal for .NET enterprise environments and making existing code AI-callable. Smaller community than LangChain but stronger typing and IDE support .



- **[Flowise](https://github.com/FlowiseAI/Flowise)**  

  Visual drag-and-drop LLM workflow builder built on LangChain — connect LLMs, prompts, tools, memory, and vector stores into working applications without code. Self-hostable and popular for teams wanting LangChain power with a visual interface .



- **[Tiledesk](https://github.com/Tiledesk/tiledesk)**  

  **Open-source alternative to Voiceflow and Botpress** — full-stack live chat with built-in chatbots, visual no-code flow designer, and LLM/GPT AI integration with graph-based conversation design .



- **[Windmill](https://github.com/windmill-labs/windmill)**  

  **Open-source Retool and Temporal alternative** — turns Python, TypeScript, Go, Bash, and SQL scripts into webhooks, workflows, and UIs with auto-generated forms. Rust backend is 13x faster than Airflow; 18k+ stars .



- **[Rivet](https://github.com/ironclad/rivet)**  

  Open-source visual AI programming environment for building AI agent chains with graph-based editor and code generation; production-ready platform .



- **[Sovrium](https://socket.dev/npm/package/sovrium)**  

  Configuration-driven web application platform — open-source alternative to Airtable, Retool, and Notion. Self-hosted with tables, automatic API, authentication, and pages defined in a config file. BSL-1.1 license .



### Additional Strong Open-Source Options



- **[CrewAI](https://github.com/joaomdmoura/crewAI)** — Multi-agent framework with crew-based orchestration and role-based agents.

- **[AutoGen (AG2)](https://github.com/microsoft/autogen)** — Microsoft's multi-agent conversation framework; forked to AG2 after Microsoft Agent Framework merger .

- **[Dify](https://github.com/langgenius/dify)** — Most-starred open-source LLM platform combining orchestration, prompt management, evaluation, and deployment.

- **[Vercel AI SDK](https://github.com/vercel/ai)** — TypeScript toolkit for building AI-powered streaming applications; different idioms from Python frameworks .

- **[OpenAI Agents SDK](https://github.com/openai/openai-agents-python)** — Official SDK for building agentic applications with handoffs and guardrails.

- **[PipesHub](https://github.com/pipeshub-ai/pipeshub)** — Open-source context layer for AI agents connecting Slack, Drive, Jira, GitHub, and Microsoft 365 .

- **[LightRAG](https://github.com/HKUDS/LightRAG)** — Simple and fast retrieval-augmented generation with knowledge graph integration .



**Frameworks for building custom systems**: Combine **LangChain** or **Haystack** for orchestration, **LlamaIndex** for data ingestion and RAG, **LangGraph** for complex agent state management, and **Flowise** or **Rivet** for visual prototyping. For enterprise .NET environments, **Semantic Kernel** provides the strongest Azure integration and type safety . For customer-facing conversational agents, **Tiledesk** delivers a fully open-source Voiceflow alternative .



**Key architectural insight**: Framework-specific patterns (orchestration topology, state management, planning strategies) vary significantly and should not be depended upon for portability. Universal patterns — tool registration via JSON Schema, MCP as interop protocol, conversation history as base memory, and structured output support — are safe to rely on across frameworks .



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- LLM frameworks manage API keys and sensitive data; ensure proper secret management and access controls when self-hosting.

- **License awareness**: Some frameworks use BSL or other non-standard licenses (e.g., Sovrium BSL-1.1) — verify commercial use terms before production deployment.

- Framework churn is high: Microsoft merged AutoGen and Semantic Kernel into Microsoft Agent Framework (October 2025), AutoGen forked to AG2, and CrewAI rebuilt without LangChain dependency. Evaluate long-term maintenance before committing .



---



**Made for AI engineers, application developers, platform teams, and open-source enthusiasts.**  
Let's make LLM application development more open, composable, and vendor-neutral.
