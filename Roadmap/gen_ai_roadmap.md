# GenAI

# Prompt Engineering
## 1. Foundations of Prompt Engineering
<details>
<summary> <strong> Introduction to Prompt Engineering </strong></summary>

* What is Prompt Engineering
* Evolution of Prompt Engineering
* Prompt vs Instruction
* Prompt Anatomy
* Components of Effective Prompts
* Prompt Design Principles
* Understanding Prompt Intent
</details>

<details>
<summary> <strong>LLM Interaction Fundamentals </strong></summary>

* How Models Interpret Prompts
* Tokenization and Prompt Impact
* Context Windows
* Attention Mechanisms and Prompt Relevance
* Instruction Following Behavior
* Prompt Sensitivity
* Positional Bias
* Recency Bias
* Lost-in-the-Middle Effect
</details>

<details>
<summary> <strong> Model Configuration & Output Parameters </strong></summary>

* Temperature
* Top-P
* Top-K
* Min-P
* Presence Penalty
* Frequency Penalty
* Repetition Penalty
* Stop Sequences
* Maximum Tokens
* Seed Control
* Deterministic Outputs
* Sampling Strategies
* Parameter Tuning Techniques
</details>

## 2. Core Prompt Construction

<details>
<summary> <strong> Instruction Design </strong></summary>

* Direct Instructions
* Explicit Instructions
* Constraint-Based Instructions
* Multi-Step Instructions
* Hierarchical Instructions
</details>


<details>
<summary> <strong> Prompt Structure </strong></summary>

* Goal Definition
* Context Definition
* Input Definition
* Output Definition
* Constraints
* Examples
* Success Criteria
</details>

<details>
<summary> <strong> Prompt Formatting </strong></summary>

* Plain Text Prompts
* Structured Prompts
* XML Prompting
* JSON Prompting
* YAML Prompting
* Markdown Prompting
</details>

<details>
<summary> <strong> Delimiter Techniques </strong></summary>

* Triple Quotes
* XML Tags
* Markdown Blocks
* Custom Delimiters
* Nested Delimiters
</details>

## 3. Basic Prompting Techniques

<details>
<summary> <strong> Zero-Shot Prompting </strong></summary>

#### Variations

* Instruction Only Prompting
* Constraint Prompting
* Role-Based Zero Shot
</details>


<details>
<summary> <strong> One-Shot Prompting </strong></summary>

#### Variations

* Demonstration Prompting
* Example-Based Prompting
</details>

<details>
<summary> <strong> Few-Shot Prompting </strong></summary>

#### Example Selection

* Static Examples
* Dynamic Examples
* Retrieval-Based Examples
* Similarity-Based Examples

#### Example Ordering

* Best Example First
* Progressive Complexity
* Contrastive Examples
</details>

## 4. Context-Oriented Prompting

<details>
<summary> <strong> Context Prompting </strong></summary>

#### Context Types

* Domain Context
* Business Context
* Historical Context
* User Context
* Task Context
</details>

### Context Injection
### Context Layering
### Context Prioritization
### Context Compression
### Dynamic Context Prompting
### Long Context Prompting
### Context Window Optimization
### Context Anchoring
### Context Refreshing Techniques

## 5. Role and Persona Prompting

### System Instruction Prompting

<details>
<summary> <strong> Persona Prompting </strong></summary>

#### Persona Types

* Professional Personas
* Expert Personas
* Domain Personas
* Fictional Personas
</details>

### Role Prompting
### Multi-Role Prompting
### Expert Panel Prompting
### Perspective Prompting
### Audience Prompting

## 6. Output Control Techniques

<details>
<summary> <strong> Output Formatting </strong></summary>

#### Structured Outputs

* JSON Mode
* XML Outputs
* YAML Outputs
* CSV Outputs
* Markdown Outputs
</details>

<details>
<summary> <strong> Style Control </strong></summary>

* Tone Prompting
* Voice Prompting
* Writing Style Prompting
* Formality Control
* Creativity Control
</details>

<details>
<summary> <strong> Length Control </strong></summary>

* Summary Prompting
* Detailed Response Prompting
* Token Budget Prompting
</details>

<details>
<summary> <strong> Output Constraints </strong></summary>

* Schema Constraints
* Rule Constraints
* Validation Constraints
</details>

## 7. Reasoning Prompting Techniques

<details>
<summary> <strong> Chain of Thought (CoT) </strong></summary>

#### Variants

* Standard CoT
* Zero-Shot CoT
* Few-Shot CoT
</details>

### Step-by-Step Prompting
### Decomposition Prompting
### Breakdown Prompting
### Sequential Reasoning
### Deductive Reasoning Prompting
### Inductive Reasoning Prompting
### Abductive Reasoning Prompting
### Causal Reasoning Prompting
### Counterfactual Reasoning Prompting
### Analytical Prompting
### Hypothesis Driven Prompting

## 8. Advanced Reasoning Frameworks

<details>
<summary> <strong> Tree of Thoughts (ToT) </strong></summary>

#### Components

* Thought Generation
* Thought Evaluation
* Search Strategies
</details>

### Graph of Thoughts (GoT)
### Self-Consistency Prompting
### Consistency Prompting
### Plan and Solve Prompting
### Least-to-Most Prompting
### Program of Thoughts (PoT)
### Skeleton of Thoughts (SoT)

<details>
<summary> <strong> ReAct Prompting </strong></summary>

#### Components

* Reasoning
* Action
* Observation
</details>

### Reflexion
### Self-Refine
### Chain of Verification (CoVe)
### Active Prompting
### Generated Knowledge Prompting
### Deliberate Reasoning Prompting

## 9. Prompt Chaining & Workflow Prompting

<details>
<summary> <strong> Prompt Chaining </strong></summary>

#### Types

* Linear Chaining
* Branching Chaining
* Recursive Chaining
</details>

### Sequential Prompting
### Pipeline Prompting
### Workflow Prompting
### Multi-Step Task Prompting
### Planning Prompting
### Execution Prompting
### Review Prompting
### Validation Prompting
### Critique Prompting
### Iterative Refinement Prompting


## 10. Meta Prompting

### Meta Prompting Fundamentals
### Prompt Generation Prompting
### Prompt Optimization Prompting
### Prompt Critique Prompting
### Prompt Self-Improvement
### Prompt Rewriting
### Prompt Mutation
### Prompt Evolution
### Prompt Search
### Automatic Prompt Generation
### Automatic Prompt Refinement


## 11. Structured Output Engineering

### JSON Mode
### Function Calling
### Tool Calling
### Schema Enforcement
### Response Validation
### Typed Outputs
### Structured Extraction
### Information Extraction Prompting
### Data Transformation Prompting
### Constrained Generation
### Grammar-Constrained Prompting


## 12. Multi-Modal Prompting

<details>
<summary> <strong> Text-to-Image Prompting </strong></summary>

#### Components

* Subject
* Style
* Composition
* Lighting
* Camera Controls
</details>

### Image Understanding Prompting
### Image Analysis Prompting
### Visual Reasoning Prompting
### Text + Image Prompting
### Audio Prompting
### Video Prompting
### Document Prompting
### OCR Prompting


## 13. Agent-Oriented Prompting

### Tool Usage Prompting
### Planning Prompting
### Action Prompting
### Observation Prompting
### Reflection Prompting
### Retry Prompting
### Error Recovery Prompting
### Task Routing Prompting
### Autonomous Agent Prompting

<details>
<summary> <strong> Multi-Agent Prompting </strong></summary>

#### Agent Patterns

* Planner Agent
* Executor Agent
* Reviewer Agent
* Critic Agent
* Debate Agent
</details>


## 14. Prompt Optimization Techniques
### Prompt Tuning
### Prompt Compression
### Prompt Simplification
### Prompt Expansion
### Prompt Distillation
### Prompt Ensembles
### Contrastive Prompting
### Comparative Prompting
### A/B Prompt Testing
### Prompt Benchmarking
### Prompt Performance Analysis


## 15. Adversarial Prompting

### Adversarial Prompt Engineering

<details>
<summary> <strong> Jailbreaking Techniques </strong></summary>

#### Common Attacks

* Roleplay Attacks
* Instruction Override Attacks
* Translation Attacks
* Encoding Attacks
* Multi-Step Jailbreaks
</details>

<details>
<summary> <strong> Prompt Injection </strong></summary>

#### Types

* Direct Injection
* Indirect Injection
* Context Injection
* Tool Injection
</details>

### Prompt Leakage
### Prompt Extraction
### Context Poisoning


## 16. Defensive Prompt Engineering
### Defensive Prompt Design
### Guardrail Prompting
### Constitutional Prompting
### Input Validation Prompting
### Output Validation Prompting
### Instruction Hierarchies
### Prompt Isolation
### Safety Prompting
### Alignment Prompting
### Robust Prompt Design


## 17. Prompt Evaluation

### Prompt Testing Fundamentals

<details>
<summary> <strong> Evaluation Metrics </strong></summary>

#### Quality Metrics

* Accuracy
* Relevance
* Completeness
* Consistency
* Robustness
</details>

### Human Evaluation
### Rubric-Based Evaluation
### Pairwise Comparison
### LLM-as-a-Judge
### Golden Dataset Evaluation
### Regression Testing
### Stress Testing
### Edge Case Testing
### Safety Testing
### Prompt Benchmarking


## 18. Prompt Management Lifecycle
### Planning
### Drafting
### Review
### Testing
### Versioning
### Storage
### Deployment
### Monitoring
### Maintenance

<details>
<summary> <strong> Retirement </strong></summary>

#### Governance

* Prompt Documentation
* Prompt Cataloging
* Prompt Reusability
* Prompt Standards
* Prompt Auditing
</details>


## 19. Prompt Engineering Frameworks & Libraries
### DSPy
### Promptfoo
### PromptLayer
### Promptmetheus
### DeepEval
### OpenAI Evals
### Braintrust
### LangSmith
### TruLens
### Ragas
### Phoenix
### LangFuse


## 20. Emerging & Research Topics
### Soft Prompting
### Prefix Prompting
### Prompt Tuning
### P-Tuning
### Automatic Prompt Optimization
### Self-Improving Prompts
### Prompt Transferability
### In-Context Learning
### Test-Time Compute Prompting
### Reasoning-Augmented Prompting
### Adaptive Prompting
### Dynamic Prompting
### Personalized Prompting
### Prompt Ensembles

---

### Optional
* Least-to-Most Prompting
* Program of Thoughts (PoT)
* Skeleton of Thoughts (SoT)
* Chain of Verification (CoVe)
* Reflexion
* Self-Refine
* Active Prompting
* Generated Knowledge Prompting
* Contrastive Prompting
* Constitutional Prompting
* Prompt Compression
* Prompt Ensembles
* Prompt Benchmarking
* Prompt Governance
* Prompt Lifecycle Management


# Context Engineering
## 1. Foundations of Context Engineering

### Introduction to Context Engineering
* What is Context Engineering
* Context Engineering vs Prompt Engineering
* Why Context Matters More Than Prompts
* Components of Context
* Context Lifecycle
* Context Quality Principles

### Understanding Context Windows
* Context Window Fundamentals
* Token Budget Management
* Effective Context Length
* Attention Distribution
* Context Saturation
* Context Overflow
* Lost-in-the-Middle Problem
* Recency Bias
* Primacy Bias

### Context Design Principles
* Relevance
* Completeness
* Freshness
* Accuracy
* Consistency
* Minimality
* Explainability


## 2. Context Construction

### Context Assembly

#### Context Sources
* User Input
* System Instructions
* Conversation History
* Retrieved Documents
* Tool Results
* Memory Systems
* External APIs
* Knowledge Bases

### Context Composition

#### Context Layers
* System Context
* User Context
* Retrieval Context
* Memory Context
* Tool Context
* Session Context
* Execution Context

### Context Ordering

#### Ordering Strategies
* Relevance First
* Chronological
* Hierarchical
* Priority Based
* Hybrid Ordering

### Context Packaging

#### Packaging Formats
* Raw Context
* Structured Context
* JSON Context
* XML Context
* Metadata-Enriched Context



## 3. Retrieval Context Engineering

### Retrieval Fundamentals

#### Retrieval Strategies
* Keyword Retrieval
* Semantic Retrieval
* Hybrid Retrieval
* Metadata Retrieval
* Graph Retrieval

### Query Construction

#### Query Optimization
* Query Expansion
* Query Rewriting
* Query Decomposition
* Multi-Query Retrieval
* Step-Back Retrieval

### Retrieval Pipelines
* Single Stage Retrieval
* Multi-Stage Retrieval
* Hierarchical Retrieval
* Cascading Retrieval
* Multi-Hop Retrieval
* Recursive Retrieval

### Document Selection

#### Chunk Selection
* Top-K Retrieval
* Adaptive Retrieval
* Dynamic Retrieval



## 4. Chunking Strategies
### Chunking Fundamentals
* Fixed Chunking
* Semantic Chunking
* Recursive Chunking
* Hierarchical Chunking
* Document-Aware Chunking
* Structure-Aware Chunking
* Sentence-Based Chunking
* Paragraph-Based Chunking
* Section-Based Chunking

### Chunk Optimization
* Chunk Size Selection
* Chunk Overlap
* Chunk Metadata
* Chunk Linking
* Parent-Child Chunks


## 5. Memory Context Engineering

### Memory Fundamentals
#### Memory Types
* Short-Term Memory
* Long-Term Memory
* Working Memory
* Episodic Memory
* Semantic Memory
* Procedural Memory

### Session Memory
* Conversation History
* Session State
* Interaction Tracking

### Persistent Memory
* User Profiles
* Preferences
* Learned Facts
* Behavioral Memory

### Memory Retrieval
* Memory Search
* Memory Ranking
* Memory Summarization
* Memory Consolidation
* Memory Decay
* Memory Refresh


## 6. Tool Context Engineering
### Tool Context Fundamentals
* Tool Outputs as Context
* Tool Result Injection
* Tool State Management
* Tool Metadata Management

### Tool Result Optimization
* Filtering
* Aggregation
* Normalization
* Formatting
* Deduplication

### Multi-Tool Context
* Tool Fusion
* Tool Chaining
* Tool Arbitration
* Tool Prioritization


## 7. Conversation Context Engineering
### Chat History Management
* Full History
* Rolling Window
* Sliding Window
* Selective Retention
* Event-Based Retention

### Conversation State
* Dialogue State Tracking
* Intent Tracking
* Goal Tracking
* Task Tracking
* User Preference Tracking

### Multi-Turn Context
* Context Carryover
* Context Refresh
* Context Repair


## 8. Context Compressio*
### Compression Fundamentals
* Lossless Compression
* Lossy Compression

### Summarization Techniques
* Extractive Summarization
* Abstractive Summarization
* Recursive Summarization
* Hierarchical Summarization
* Running Summaries

### Compression Strategies
* Semantic Compression
* Context Distillation
* Fact Extraction
* Information Consolidation
* Redundancy Removal


## 9. Context Pruning
### Pruning Fundamentals
* Token-Based Pruning
* Relevance-Based Pruning
* Importance-Based Pruning
* Age-Based Pruning
* Confidence-Based Pruning

### Context Filtering
* Duplicate Removal
* Noise Removal
* Irrelevant Content Removal
* Contradictory Context Removal

### Dynamic Pruning
* Adaptive Pruning
* Query-Aware Pruning
* Task-Aware Pruning


## 10. Context Ranking & Reranking
### Ranking Fundamentals
* Relevance Ranking
* Semantic Ranking
* Similarity Ranking
* Diversity Ranking

### Reranking Techniques
* Cross Encoder Reranking
* LLM Reranking
* Hybrid Reranking
* Multi-Stage Reranking

### Context Prioritization
* Importance Scoring
* Utility Scoring
* Freshness Scoring
* Trust Scoring



## 11. Long Context Engineering
### Long Context Fundamentals
* Large Context Windows
* Effective Context Utilization
* Context Dilution
* Context Saturation
* Long Context Failure Modes

### Long Context Strategies
* Sliding Window Retrieval
* Hierarchical Context
* Context Partitioning
* Context Chunk Routing
* Progressive Retrieval
* Recursive Retrieval
* Layered Retrieval

### Long Context Optimization
* Context Anchoring
* Context Positioning
* Retrieval Refreshing
* Memory Compression


## 12. Long Context Models
### Architecture Fundamentals
* Transformer Limitations
* Sparse Attention
* Linear Attention
* Memory-Augmented Attention
* Retrieval-Augmented Attention

### Model Categories
* Standard Context Models
* Extended Context Models
* Infinite Context Architectures
* Streaming Context Architectures

### Long Context Evaluation
* Needle-in-a-Haystack Testing
* Recall Evaluation
* Long Range Reasoning Tests


## 13. Context Routing
### Routing Fundamentals
* Context Selection
* Context Classification
* Context Routing Policies

### Dynamic Routing
* Query-Aware Routing
* Task-Aware Routing
* User-Aware Routing
* Intent-Aware Routing

### Multi-Source Routing
* Memory Routing
* Retrieval Routing
* Tool Routing
* Knowledge Base Routing


## 14. Multi-Source Context Fusion
### Fusion Fundamentals
* Retrieval + Memory Fusion
* Retrieval + Tool Fusion
* Memory + Tool Fusion
* Multi-Modal Fusion

### Conflict Resolution
* Contradiction Detection
* Confidence Resolution
* Source Prioritization
* Truth Arbitration

### Context Merging
* Deduplication
* Consolidation
* Context Synthesis


## 15. Context Quality Management
### Context Quality Metrics
* Relevance
* Coverage
* Freshness
* Accuracy
* Consistency
* Diversity
* Utility

### Context Validation
* Fact Validation
* Source Validation
* Context Consistency Checks
* Contradiction Detection


## 16. Context Security
### Secure Context Construction
* Sensitive Data Filtering
* PII Removal
* Data Sanitization
* Access Control

### Context Attacks
* Context Poisoning
* Retrieval Poisoning
* Memory Poisoning
* Indirect Prompt Injection
* Retrieval-Based Prompt Injection

### Defensive Context Engineering
* Context Isolation
* Source Verification
* Context Validation
* Trust Scoring


## 17. Context Evaluation
### Evaluation Fundamentals
* Offline Evaluation
* Online Evaluation
* Human Evaluation
* Automated Evaluation

### Retrieval Evaluation
* Precision
* Recall
* MRR
* NDCG
* Hit Rate

### Context Evaluation Metrics
* Relevance Score
* Coverage Score
* Freshness Score
* Context Utility Score
* Grounding Score

### Failure Analysis
* Missing Context
* Incorrect Context
* Redundant Context
* Hallucination Root Cause Analysis


## 18. Advanced Context Engineering Patterns

### Context Caching
* Retrieval Caching
* Memory Caching
* Semantic Caching

### Context Distillation
### Context Graphs
### Knowledge Graph Context
### Context Hierarchies
### Context Templates
### Dynamic Context Generation
### Self-Improving Context Systems
### Adaptive Context Systems
### Agentic Context Management


## Most overlooked Context Engineering topics are:
* Context Routing
* Multi-Source Context Fusion
* Context Ranking & Reranking
* Context Ordering Strategies
* Context Quality Evaluation
* Context Compression Architectures
* Memory Consolidation
* Context Conflict Resolution
* Context Anchoring
* Context Security & Poisoning Defense


# Model Calling

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




