# AI/ML/GenAI Master Course — 12-Month Plan

## Course Philosophy

Learn by building, then learn the mathematics behind what was built, implement core ideas from scratch, use real frameworks, and repeat with progressively larger projects.

For important concepts:

**Theory → Why → When → Math → From-scratch implementation → Framework → Hands-on → Project → Interview/Revision**

## 12-Month Roadmap

### Phase 0 — Python for AI (2 weeks)
- Python fundamentals for AI/ML
- NumPy
- Pandas
- Matplotlib
- Hands-on: Data Analysis Notebook

### Phase 1 — Math for ML: Linear Algebra (~8 weeks)
- Scalars, vectors, dimensions
- Vector operations and norms
- Dot product and cosine similarity
- Matrices and matrix operations
- Matrix multiplication
- Transpose, inverse, rank
- Linear transformations
- Basis and span
- Orthogonality and projections
- Eigenvalues and eigenvectors
- Singular Value Decomposition (SVD)
- PCA
- Hands-on: vector operations, matrix multiplication, cosine similarity, transformations, projections, PCA

### Phase 2 — Probability & Statistics (~3 weeks)
- Probability
- Conditional probability
- Independence
- Bayes theorem
- Random variables
- Expectation and variance
- Covariance
- Bernoulli, binomial, Gaussian, uniform, Poisson distributions
- Mean, median, standard deviation
- Correlation and covariance
- Sampling
- Central Limit Theorem
- Confidence intervals
- Hypothesis testing
- Hands-on: probability/statistics simulation lab

### Phase 3 — Calculus & Optimization (~3 weeks)
- Derivatives
- Partial derivatives
- Chain rule
- Gradients
- Jacobian concept
- Optimization
- Gradient descent
- Learning rate
- Local/global minima
- Convexity
- Batch, stochastic and mini-batch gradient descent
- Hands-on: gradient descent and linear regression from scratch

### Phase 4 — Classical ML (~6 weeks)
#### Regression
- Linear regression
- Polynomial regression
- Ridge
- Lasso

#### Classification
- Logistic regression
- KNN
- Naive Bayes
- Decision trees

#### Ensembles
- Bagging
- Random forest
- Boosting
- Gradient boosting
- XGBoost

#### Unsupervised Learning
- KMeans
- Hierarchical clustering
- DBSCAN
- PCA

#### ML Fundamentals
- Train/validation/test split
- Overfitting and underfitting
- Bias/variance
- Regularization
- Cross-validation
- Feature engineering
- Feature scaling
- Data leakage
- Evaluation metrics

**Major Project #1:** End-to-End ML Prediction System

### Phase 5 — Neural Networks From Scratch (~4 weeks)
- Perceptron
- z = Wx + b
- Sigmoid
- Tanh
- ReLU
- Leaky ReLU
- Softmax
- MSE
- Binary cross-entropy
- Cross-entropy
- Forward pass
- Loss calculation
- Backpropagation
- Gradients
- Parameter updates
- Hands-on: NumPy neural network on XOR, then MNIST

### Phase 6 — PyTorch (~3 weeks)
- Tensor
- Dataset
- DataLoader
- nn.Module
- Linear layers
- Activations
- Loss functions
- Optimizers
- Autograd
- GPU usage
- Checkpoints
- Training loops
- Validation loops
- Hands-on: rebuild the NumPy neural network in PyTorch

### Phase 7 — Deep Learning (~5 weeks)
- CNNs
- Convolution and kernels
- Feature maps
- Padding
- Stride
- Pooling
- Receptive field
- Transfer learning
- RNNs
- LSTMs
- GRUs
- Sequence-model limitations

**Project #2:** Image Classifier

### Phase 8 — Embeddings (1–2 weeks)
- Text → tokens → embeddings → vectors
- Semantic similarity
- Cosine similarity
- Vector distance
- Hands-on: semantic search engine

### Phase 9 — Transformers (~5 weeks)
- Why Transformers
- Attention
- Query, Key, Value
- Attention(Q, K, V)
- Multi-head attention
- Positional encoding
- Residual connections
- Layer normalization
- Feed-forward networks
- Encoder/decoder architecture
- Causal masking
- Hands-on: self-attention from scratch and a mini Transformer

### Phase 10 — LLMs (~4 weeks)
- Tokenization
- BPE
- Vocabulary
- Context window
- Next-token prediction
- Causal language modeling
- Pretraining
- Inference
- Sampling
- Temperature
- Top-k
- Top-p

**Project #3:** Mini GPT

### Phase 11 — Fine-Tuning (~3 weeks)
- Pretraining vs fine-tuning
- Instruction tuning
- SFT
- LoRA
- QLoRA
- PEFT
- Quantization
- Hands-on: fine-tune an open model

### Phase 12 — GenAI Engineering (~4 weeks)
- LLM APIs
- Prompting
- Structured outputs
- Tool/function calling
- Streaming
- Retries
- Error handling
- Prompt engineering
- Prompt injection

### Phase 13 — RAG (~4 weeks)
- Document ingestion
- Parsing
- Chunking
- Embeddings
- Vector databases
- Retrieval
- Reranking
- Context construction
- LLM answer generation
- Chunking strategies
- Metadata filtering
- Hybrid search
- Query rewriting
- Reranking
- Citations
- RAG evaluation

**Major Project #4:** Production RAG Assistant

### Phase 14 — AI Agents (~4 weeks)
- LLM → decision → tool selection → execution → observation → next action
- Tool calling
- Agents vs workflows
- State
- Memory
- Planning
- Orchestration
- Retries
- Human-in-the-loop
- Guardrails
- Structured outputs
- Agent evaluation

### Phase 15 — MCP (2 weeks)
- MCP architecture
- MCP server/client
- Tools
- Resources
- Prompts
- Authentication
- Sessions
- Hands-on: own MCP server connected to an agent

### Phase 16 — AI Evaluation & Reliability (~2 weeks)
- Correctness
- Relevance
- Groundedness
- Hallucination
- Faithfulness
- Retrieval precision
- Retrieval recall
- MRR
- NDCG
- Evaluation datasets
- Automated testing

### Phase 17 — Production AI (~5 weeks)
- FastAPI
- REST APIs
- Async programming
- Streaming
- Docker
- CI/CD
- AWS
- S3
- ECS/EKS concepts
- Databases
- Redis
- Queues
- Model serving
- Batching
- Caching
- Quantization
- GPU inference
- Latency
- Throughput
- Cost optimization
- Observability

### Phase 18 — MLOps
- Data → experiment → training → model → registry → deployment → monitoring → retraining
- Experiment versioning
- Model versioning
- Data versioning
- Model registry
- CI/CD
- Monitoring
- Data/model drift
- Reproducibility

### Phase 19 — Capstone (4–6 weeks)

**Software Change Impact Agent**

Architecture:

Git repository → repository parser → code retrieval + dependency graph → AI agent → tools (search/Git/tests) → impact analysis → structured report

The capstone should integrate:
- Python
- LLMs
- Embeddings
- RAG
- Vector database
- AI agent
- MCP
- Structured outputs
- Evaluation
- FastAPI
- Docker
- AWS
- Monitoring

## Suggested Monthly Timeline

| Month | Focus |
|---|---|
| 1 | Python + Linear Algebra |
| 2 | Linear Algebra + Probability |
| 3 | Statistics + Calculus + Optimization |
| 4 | Classical ML |
| 5 | Classical ML + Neural Networks |
| 6 | Neural Networks + PyTorch |
| 7 | Deep Learning + CNN + RNN |
| 8 | Embeddings + Transformers |
| 9 | LLMs + Mini GPT + Fine-Tuning |
| 10 | RAG + Vector DB + Evaluation |
| 11 | Agents + MCP + AI Engineering |
| 12 | Production AI + AWS + Capstone |

## Weekly Study Pattern

For approximately 2–3 hours/day:

- 45 min: math/theory
- 60 min: ML/DL/GenAI
- 60–90 min: hands-on coding
- One day each week: revision, interview practice, and project improvement

## Learning Checkpoint System

Every major phase should have a checkpoint covering:
- Can explain
- Can implement
- Can solve
- Weak areas
- Revision points
- Project status

The detailed course conversations can happen in separate chats. The repository is the durable course source of truth, while ChatGPT maintains a compact progress checkpoint.

## Working Model

Use GitHub PRs for meaningful course checkpoints:

1. Create/update work on a course branch.
2. Commit the changes.
3. Open a Pull Request into `main`.
4. Review the PR.
5. Merge only after review.
6. `main` remains the official course history.

Do not depend on one long ChatGPT conversation. When a conversation becomes too long, start a new one and use:

> Continue my AI/ML Master Course.

## Current Starting Point

**Current phase:** Phase 1 — Math for ML: Linear Algebra

**Current structure:**
- `Math/Theory/README.md`
- `Math/Hands-On/README.md`

**Next lesson:** Linear Algebra — Scalars, Vectors, Dimensions & Dot Product

**Current course PR:** PR #1 — Add Mathematics theory and hands-on structure
