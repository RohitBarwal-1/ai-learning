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


---

