# Sai Manojna Velagala

**Software & Data Engineer turned AI Builder**  
I build AI systems — agents, retrieval pipelines, and the infra to run them.

Four years running analytics infrastructure at GE Vernova across 20+ 
industrial plants taught me what breaks when AI meets the real world: 
messy signals, silent drift, and follow-through that dies between shifts. 
Now I build systems designed for exactly that environment.

Currently finished MS in Data Science & AI (4.0 GPA) while shipping 
agent-native projects. Open to AI engineer roles.
LLM Agents · RAG Pipelines · Production MLOps · MS Data Science & AI (4.0 GPA)

---

## What I Build

- **LLM Agents** — multi-agent pipelines with LangGraph, GPT-4o, and custom MCP servers
- **RAG Systems** — end-to-end retrieval pipelines using FAISS, pgvector, and local LLMs
- **MLOps & Infra** — containerized microservices, ArgoCD GitOps, CI/CD, observability stacks
- **ML Models** — transformer fine-tuning with LoRA/PEFT, benchmarking across model families

---

## Featured Projects

### [Agentic Code Review System](https://github.com/SManojna/agentic-code-review)
LangGraph ReAct agent that receives GitHub PR webhooks, fetches diffs, 
retrieves the top-3 most similar past reviews via pgvector similarity search, 
and posts a context-aware review comment — all orchestrated through a custom 
MCP server. Includes a feedback loop (thumbs up/down votes stored in Supabase) 
and a deployed Next.js dashboard showing review history and a 7-day activity chart.  
`LangGraph` `MCP` `GPT-4o` `pgvector` `FastAPI` `Supabase` `Next.js` `Cloud Run`

### [ClaimCheck](https://github.com/SManojna/claimcheck)
Full-stack AI fact-checker for YouTube videos — extracts claims, verifies each against the transcript using a local RAG pipeline, and returns verdicts with confidence scores and timestamp evidence. Conversational Q&A with full memory. Runs entirely on-device.  
`Next.js 14` `TypeScript` `Llama 3.1:8b` `Ollama` `nomic-embed-text` `SSE` `Tailwind CSS` `shadcn/ui`

---

### [Flight Fare Prediction & LoRA Fine-Tuning](https://github.com/SManojna/Flight_fare_prediction_llm_comparision)
Multi-model benchmark across RandomForest, K-Fold DNN, and Gemini (zero-shot / few-shot / CoT) for price-bucket classification. Fine-tuned a HuggingFace transformer using LoRA/PEFT — competitive accuracy with only 0.1% trainable parameters vs full fine-tune.  
`PyTorch` `LoRA/PEFT` `HuggingFace` `Gemini API` `Streamlit` `Scikit-learn`

---

### [Zeek Phishing Infrastructure Detection](https://github.com/SManojna/zeek-meta-graph-phishing-detection)
Critical analysis and conceptual framework applying Graph Attention Networks and meta-graph attention to Zeek network logs for detecting coordinated phishing campaigns from relational patterns.  
`PyTorch Geometric` `GAT` `Zeek` `Graph Neural Networks` `Network Forensics`

---

### [RAG Metadata Explorer — Critical Review](https://github.com/SManojna/rag-metadata-explorer-review)
Critical review of a 2024 IEEE Big Data paper on RAG-based metadata exploration — evaluates ChromaDB retrieval, LLM refinement, and embedding model comparisons across four dataset discovery tasks.  
`ChromaDB` `SBERT` `BERT` `Llama 3` `OpenAI Embeddings` `Cosine Similarity`

---

### [Deep Learning | Neural Net Implementations](https://github.com/SManojna/neural-net-implementations)
Neural network engine, CNN architectures, and sequence models built entirely in NumPy — 
no PyTorch, no autograd. Includes Conv2D transposed convolution backward pass, 
BatchNorm2D, multi-head self-attention, LSTM/GRU from scratch, beam search, 
and gradient checking.  
`NumPy` `CNN` `LSTM` `Attention` `Backpropagation` `From Scratch`

---
## Tech Stack

**AI & ML:** PyTorch · LangGraph · LoRA/PEFT · RAG · pgvector · FAISS · HuggingFace · LLM Eval  
**Cloud & DevOps:** AWS · Docker · ArgoCD · CI/CD · CloudFoundry  
**Observability:** OpenTelemetry · Elasticsearch · Kibana · Airflow  
**Languages:** Python · TypeScript · Java · SQL  

---

## Background

Four years of production software engineering across full-stack development,
distributed analytics platforms, and cloud-native infrastructure at GE Vernova
and Infosys — now focused on building applied AI systems.

📄 [LinkedIn](https://www.linkedin.com/in/sai-manojna-velagala/)  
📧 vsaimanojna@gmail.com
