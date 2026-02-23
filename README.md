# Awesome GCP LLM Projects
[![Last Commit](https://img.shields.io/github/last-commit/msampathkumar/awesome-gcp-llm-projects)](https://github.com/msampathkumar/awesome-gcp-llm-projects/commits/main)

A curated collection of Awesome Google Cloud Platform LLM apps built with RAG, AI Agents, Multi-agent Teams, MCP, Voice Agents, and more. This repository features LLM apps that use models from Google (Gemini Models) and Vertex AI Model Garden(Gemini, Gemma, DeepSeek, Claude and many more).

## Projects

### AI Agents & Templates
- [Google Antigravity](https://developers.googleblog.com/build-with-google-antigravity-our-new-agentic-development-platform/) - Google's new agentic development platform for building autonomous systems with visual verification. #Agents #Antigravity #Autonomous
- [Google Cloud Managed MCP Servers](https://cloud.google.com/blog/products/databases/managed-mcp-servers-for-google-cloud-databases) - Managed MCP support for AlloyDB, Spanner, Cloud SQL, Bigtable, and Firestore. #MCP #Databases #Agents
- [Agent Starter Pack](https://github.com/GoogleCloudPlatform/agent-starter-pack) - Production-ready templates for shipping AI Agents to Google Cloud in minutes. #Agents #Templates
- [Employee Onboarding Agent with ADK](https://cloud.google.com/blog/topics/developers-practitioners/how-to-build-onboarding-agents-with-gemini-enterprise) - Guide on using Agent Development Kit (ADK) and Agent Engine for enterprise agents. #Agents #ADK #Enterprise
- [Gemini Enterprise Agent Ready (GEAR)](https://cloud.google.com/blog/products/ai-machine-learning/gear-program-now-available) - New program and tools for building AI agents at scale on Vertex AI. #Agents #Enterprise
- [Open Data QnA](https://github.com/GoogleCloudPlatform/Open_Data_QnA) - Library for chatting with databases using LLM Agents on Google Cloud (NL2SQL). #NL2SQL #Agents

- [Daggr](https://huggingface.co/blog/daggr) - A programmatic tool for chaining applications with visual inspection, bridging the gap between scripts and full agentic loops. #Agents #Automation #VisualInspection
- [Agno](https://github.com/agno-ai/agno) - Build multi-modal agents with model-agnostic control and integrated knowledge. #Agents #MultiModal
- [Browser Use](https://github.com/browser-use/browser-use) - Make any LLM operate a browser like a human. #Agents #BrowserAutomation
- [Letta](https://github.com/letta-ai/letta) - Control plane for stateful AI agents (formerly MemGPT). #Agents #Stateful
- [mem0](https://github.com/mem0ai/mem0) - The memory layer for AI agents. #Agents #Memory
- [Eigent](https://github.com/eigent-ai/eigent) - High-performance agent framework for enterprise-scale autonomous workflows. #Agents #Enterprise #Autonomous

### Model Context Protocol (MCP)
- [Official Google Remote MCP Servers](https://docs.cloud.google.com/mcp/supported-products) - Comprehensive list of Google Cloud products accessible through remote MCP servers.
  - **Databases**: [AlloyDB](https://cloud.google.com/alloydb/docs/ai/use-alloydb-mcp), [BigQuery](https://cloud.google.com/bigquery/docs/reference/mcp), [Bigtable](https://cloud.google.com/bigtable/docs/use-bigtable-mcp), [Cloud SQL](https://cloud.google.com/sql/docs/mysql/use-cloudsql-mcp), [Firestore](https://cloud.google.com/firestore/native/docs/use-firestore-mcp), [Spanner](https://cloud.google.com/spanner/docs/use-spanner-mcp).
  - **Infrastructure**: [Compute Engine](https://cloud.google.com/compute/docs/reference/mcp), [GKE](https://cloud.google.com/kubernetes-engine/docs/reference/mcp), [Resource Manager](https://cloud.google.com/resource-manager/reference/mcp).
  - **Operations**: [Cloud Logging](https://cloud.google.com/logging/docs/reference/v2/mcp), [Cloud Monitoring](https://cloud.google.com/monitoring/api/ref_v3/mcp).
  - **Security**: [Google Security Operations](https://cloud.google.com/chronicle/docs/reference/mcp).
  - **Knowledge & Maps**: [Developer Knowledge API](https://developers.google.com/knowledge/api), [Maps Grounding Lite](https://developers.google.com/maps/ai/grounding-lite).
- [Google Cloud Developer Knowledge MCP](https://developers.google.com/knowledge/mcp) - Connects IDEs to Google’s documentation via MCP for technical troubleshooting. #MCP #Developers
- [Gemini Cloud Assist MCP](https://github.com/GoogleCloudPlatform/gemini-cloud-assist-mcp) - MCP Server for Gemini Cloud Assist providing tools for GCP tasks. #MCP #CloudAssist
- [Google MCP GitHub Repository](https://github.com/Google/mcp) - Collection of local MCP servers maintained by Google.

### Platforms & Frameworks
- [LiteRT](https://developers.googleblog.com/litert-the-universal-framework-for-on-device-ai/) - Formerly TFLite, now 1.4x faster for on-device AI. Optimized for Gemma on mobile. #LiteRT #OnDeviceAI #EdgeAI
- [Google Cloud Creative Studio](https://github.com/GoogleCloudPlatform/gcc-creative-studio) - Comprehensive GenAI Platform and reference implementation on Vertex AI. #Platform #VertexAI
- [GenMedia Creative Studio](https://github.com/GoogleCloudPlatform/vertex-ai-creative-studio) - A Vertex AI generative media experience highlighting Imagen, Veo, and Gemini APIs. #GenMedia #VertexAI #Creatives
- [Google Flow](https://labs.google/flow/) - An experimental tool from Google Labs for building and visualizing AI workflows. #Flow #AIWorkflows #Labs

### Tools & CLI
- [Gemini CLI](https://geminicli.com/) - A command-line interface for interacting with Googles Gemini models. #CLI #Gemini #Developers
- [Google AI Studio](https://aistudio.google.com/) - A fast way to build with Gemini models and get API keys. #AIStudio #Gemini #API

### Industry Specific
- [Voicebox](https://github.com/jamiepine/voicebox) - A local-first voice synthesis studio with DAW-like features for professional voice synthesis. #Voice #Synthesis #LocalFirst
- [EssAI](https://github.com/GoogleCloudPlatform/essai) - Automated essay grading for educators using Google Gemini. #Education #Gemini

### Code & Samples
- [Generative AI Samples](https://github.com/GoogleCloudPlatform/generative-ai) - Sample code and notebooks for Generative AI on Google Cloud, with Gemini on Vertex AI. #GenerativeAI #VertexAI #Gemini #Samples
- [Gen AI for Svelte](https://github.com/lassestilvang/gen-ai-for-svelte) - A simple Svelte project using Google Vertex AI to do a simple prompt and display the results. #Web #Svelte #VertexAI #Gemini

### Multi-Agent Systems
- [ARBITER](https://github.com/sambhandavale/arbiter) - An adversarial multi-agent platform powered by Google ADK and Gemini that cross-examines supply chain claims. #MultiAgent #ADK #Gemini #SupplyChain
- [Sentinel](https://github.com/aditya-ai-architect/Sentinel) - An autonomous multi-agent competitive intelligence platform with a 5-agent orchestration chain. #MultiAgent #CompetitiveIntelligence #Gemini

### RAG & Multimodal
- [GCP Multimodal AI RAG](https://github.com/nikolailen/gcp-multimodal-ai-rag) - A multimodal AI knowledge base with RAG on GCP, using Gemini for parsing, BigQuery for vectors, and LangChain. #RAG #Multimodal #Gemini #BigQuery
- [F.R.I.D.A.Y](https://github.com/aditya-ai-architect/F.R.I.D.A.Y) - A 3D Intelligence Engine with real-time voice, vision, and gesture control, powered by Gemini 3.0 Pro. #3D #Multimodal #VoiceAI #Vision #Gemini

### Industry Specific
- [AI Healthcare System](https://github.com/pavanbadempet/AI-Healthcare-System) - AI-powered healthcare platform combining Machine Learning for multi-disease prediction with Generative AI for intelligent medical assistance. #Healthcare #Gemini #RAG
- [EdGrab](https://github.com/aditya-ai-architect/EdGrab) - An AI-Powered Tutoring Platform with real-time voice AI, adaptive learning, and persistent memory. #EdTech #VoiceAI #Gemini #AdaptiveLearning
- [IFRS 9 AI Agent](https://github.com/japponjotsingh/ifrs9-ai-agent) - An autonomous AI agent for IFRS 9 credit risk analysis using Google Gemini and BigQuery. #Finance #AutonomousAgent #Gemini #BigQuery

### Chatbots & Assistants
- [Auto-cpufreq GenAI Chatbot](https://github.com/AdnanHodzic/auto-cpufreq-genAI-chatbot) - A GenAI chatbot for auto-cpufreq, built using Vertex AI Agent Builder and powered by Gemini. #Chatbot #VertexAI #AgentBuilder #Gemini
- [Voice Input Assistant](https://github.com/yuhao-he/voice-input-assistant) - A cloud-based voice input assistant using GCP and Gemini for enhanced productivity. #Voice #Productivity #Gemini

---
Maintainer: [@msampathkumar](https://github.com/msampathkumar)
