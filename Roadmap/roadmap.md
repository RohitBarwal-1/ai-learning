# AI Mastery Roadmap

## Table of Contents

- Foundations
- GenAI
- RAG
- Agentic AI
- AI Automation
- Multimodal AI
- LLMs
- LLMOps
- AI Infrastructure
- AI Security
- AI System Design
- Optional ML Foundations

---

# Foundations

<details>
<summary><strong>Python</strong></summary>

### Core Python

- OOP
- Functional Programming
- Decorators
- Generators
- AsyncIO
- Context Managers
- Type Hints

### Data Processing

- NumPy
- Pandas
- Polars
- PyArrow

### APIs

- REST
- GraphQL
- WebSockets
- Streaming APIs

### Backend

- FastAPI
- Authentication
- Middleware
- Dependency Injection

### Databases

- PostgreSQL
- MongoDB
- Redis

### Distributed Systems Basics

- Caching
- Queues
- Pub/Sub
- Event Driven Systems

</details>

<details>
<summary><strong>LangChain</strong></summary>

### Chains

- Sequential Chains
- Router Chains

### Memory

- Buffer Memory
- Summary Memory
- Entity Memory

### Retrieval

- Retriever APIs
- Compression Retrievers

### Tools

- Custom Tools
- Toolkits

### Agents

- ReAct Agents
- Tool Calling Agents

</details>

<details>
<summary><strong>LangGraph</strong></summary>

### Graph Fundamentals

- Nodes
- Edges
- State

### Agent Workflows

- Planning
- Reflection
- Human-in-the-loop

### Persistence

- Checkpointing
- Memory

</details>

---

# GenAI

<details>
<summary><strong>Prompt Engineering</strong></summary>

### Basic Prompting

- Zero Shot
- One Shot
- Few Shot

### Advanced Prompting

- Chain of Thought
- Self Consistency
- Tree of Thoughts
- ReAct
- DSPy
- Prompt Chaining

### Structured Outputs

- JSON Mode
- Function Calling
- Schema Enforcement

</details>

<details>
<summary><strong>Context Engineering</strong></summary>

### Context Construction

- Retrieval Context
- Memory Context
- Tool Context

### Context Compression

- Summarization
- Context Pruning
- Reranking

### Long Context

- Long Context Models
- Sliding Window Retrieval

</details>

<details>
<summary><strong>Model Calling</strong></summary>

### API Providers

- OpenAI
- Anthropic
- Gemini
- Open Source Models

### Generation Controls

- Temperature
- Top-P
- Top-K
- Frequency Penalty
- Presence Penalty

### Streaming

- Token Streaming
- Event Streaming

</details>

</details>

---

# RAG

<details>
<summary><strong>Document Processing</strong></summary>

### Extraction

- PDFs
- OCR
- HTML
- Tables

### Cleaning

- Deduplication
- Normalization
- Metadata Enrichment

</details>

<details>
<summary><strong>Chunking</strong></summary>

### Traditional

- Fixed Size
- Recursive

### Advanced

- Semantic Chunking
- Agentic Chunking
- Hierarchical Chunking

</details>

<details>
<summary><strong>Embeddings</strong></summary>

### Fundamentals

- Vector Space
- Similarity Search

### Models

- OpenAI
- BGE
- E5
- Jina

### Metrics

- Cosine Similarity
- Dot Product
- Euclidean Distance

</details>

<details>
<summary><strong>Vector Databases</strong></summary>

### Databases

- Pinecone
- Weaviate
- Qdrant
- Milvus

### Indexes

- HNSW
- IVF
- PQ

</details>

---

# Agentic AI

<details>
<summary><strong>Workflows</strong></summary>

### Workflow Patterns

- Sequential
- Parallel
- Conditional
- Event Driven

</details>

<details>
<summary><strong>Tool Calling</strong></summary>

### Tools

- Function Calling
- API Tools
- Database Tools
- Browser Tools
- Code Execution

</details>

<details>
<summary><strong>Planning</strong></summary>

### Agent Reasoning

- ReAct
- Plan-and-Execute
- LLM Compiler
- Reflection
- Self-Correction

</details>

<details>
<summary><strong>MCP</strong></summary>

### Fundamentals

- MCP Architecture
- MCP Clients
- MCP Servers

### Components

- Resources
- Tools
- Prompts

</details>

---

# AI Automation

<details>
<summary><strong>Automation Types</strong></summary>

- Rule Based
- LLM Driven
- Agent Driven
- Human-in-the-loop

</details>

<details>
<summary><strong>Automation Tools</strong></summary>

- n8n
- Make
- Zapier
- Temporal
- Airflow

</details>

---

# Multimodal AI

<details>
<summary><strong>Vision</strong></summary>

- OCR
- Object Detection
- Image Captioning
- VLMs

</details>

<details>
<summary><strong>Speech</strong></summary>

- ASR
- TTS
- Voice Agents
- Speaker Diarization

</details>

<details>
<summary><strong>Video</strong></summary>

- Video Understanding
- Video Generation

</details>

<details>
<summary><strong>Image Generation</strong></summary>

- Diffusion Models
- ControlNet
- Image Editing

</details>

---

# LLMs

<details>
<summary><strong>Transformer Architecture</strong></summary>

### Core Components

- Self Attention
- Multi Head Attention
- Feed Forward Networks
- Residual Connections
- LayerNorm
- Positional Encoding

</details>

<details>
<summary><strong>Training Pipeline</strong></summary>

### Pretraining

- Next Token Prediction
- Data Curation

### Alignment

- SFT
- RLHF
- DPO

</details>

<details>
<summary><strong>Inference</strong></summary>

### Optimization

- KV Cache
- Speculative Decoding
- Continuous Batching

</details>

---

# LLMOps

<details>
<summary><strong>Model Deployment</strong></summary>

### Serving Frameworks

- vLLM
- TGI
- Ollama
- SGLang

### Infrastructure

- GPUs
- Kubernetes
- Autoscaling

</details>

<details>
<summary><strong>Finetuning</strong></summary>

### Techniques

- Full Finetuning
- PEFT
- LoRA
- QLoRA

</details>

<details>
<summary><strong>Quantization</strong></summary>

### Methods

- GPTQ
- AWQ
- GGUF
- BitsAndBytes

</details>

---

# AI Infrastructure

<details>
<summary><strong>Compute</strong></summary>

### Hardware

- CPU
- GPU
- TPU

### CUDA

- Kernels
- Memory Management
- Streams

</details>

<details>
<summary><strong>Distributed Systems</strong></summary>

### Platforms

- Ray
- Kubernetes

### AI Scaling

- Distributed Inference
- Distributed Training

</details>

---

# AI Security

<details>
<summary><strong>Prompt Security</strong></summary>

- Prompt Injection
- Jailbreaks
- Prompt Leakage

</details>

<details>
<summary><strong>Data Security</strong></summary>

- PII Protection
- Secrets Management
- Governance

</details>

---

# AI System Design

<details>
<summary><strong>Reliability</strong></summary>

- Retries
- Circuit Breakers
- Fallback Models

</details>

<details>
<summary><strong>Scalability</strong></summary>

- Horizontal Scaling
- Load Balancing

</details>

<details>
<summary><strong>Latency Optimization</strong></summary>

- Streaming
- Caching
- Batching

</details>

---

# Optional ML Foundations

<details>
<summary><strong>Mathematics</strong></summary>

- Linear Algebra
- Probability
- Statistics
- Calculus

</details>

<details>
<summary><strong>Machine Learning</strong></summary>

- Supervised Learning
- Unsupervised Learning
- Evaluation Metrics

</details>

<details>
<summary><strong>Deep Learning</strong></summary>

- Neural Networks
- Backpropagation
- CNNs
- RNNs

</details>
