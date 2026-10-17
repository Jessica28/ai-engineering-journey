# 🚀 AI Engineering Journey

A rigorous, 6-month production-focused curriculum and portfolio designed to transition into a professional **AI Engineer** role. 

This repository serves as the master tracking hub for my daily studies, architectural blueprints, and hands-on portfolio projects covering advanced RAG, agentic workflows, LLMOps, and cloud engineering.

---

## 📐 System Architecture Blueprint

```mermaid
graph TD
    %% Styling Classes
    classDef foundation fill:#E0F2FE,stroke:#0284C7,stroke-width:2px,color:#0F172A;
    classDef core fill:#DCFCE7,stroke:#16A34A,stroke-width:2px,color:#0F172A;
    classDef cloud fill:#FEF3C7,stroke:#D97706,stroke-width:2px,color:#0F172A;
    classDef ops fill:#F3E8FF,stroke:#9333EA,stroke-width:2px,color:#0F172A;
    classDef capstone fill:#FEE2E2,stroke:#DC2626,stroke-width:2px,color:#0F172A;

    subgraph M1 ["Month 1: Foundation Layer"]
        M1_Task["Async Python, Pydantic v2 & API Engineering<br>• FastAPI Microservice Wrapper<br>• Strict JSON Schema & Tokenomics"]:::foundation
    end

    subgraph M2 ["Month 2: Knowledge Layer"]
        M2_Task["Advanced RAG & Vector Search<br>• Hybrid Search (BM25 + Vectors)<br>• Qdrant Indexing & Cohere Rerank"]:::core
    end

    subgraph M3 ["Month 3: Execution Layer"]
        M3_Task["Agentic Workflows & Multi-Tool Systems<br>• LangGraph Stateful Loops<br>• Model Context Protocol (MCP)"]:::core
    end

    subgraph M4 ["Month 4: Cloud Validation"]
        M4_Task["Cloud Architecture & Certification<br>• Azure AI-102 or AWS AIF-C01<br>• Enterprise Security & IAM"]:::cloud
    end

    subgraph M5 ["Month 5: Reliability & Ops Layer"]
        M5_Task["Evals, LLMOps & Local Fine-Tuning<br>• LangSmith Tracing & LLM-as-a-Judge<br>• vLLM & PEFT/LoRA Quantization"]:::ops
    end

    subgraph M6 ["Month 6: Capstone & Career Launch"]
        M6_Task["Production Platform Capstone<br>• Full-Stack App Deployment<br>• GitHub Architecture & Applications"]:::capstone
    end

    %% Pipeline Flow
    M1_Task --> M2_Task
    M2_Task --> M3_Task
    M3_Task --> M4_Task
    M4_Task --> M5_Task
    M5_Task --> M6_Task
