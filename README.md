# 120 Days of ML From Scratch

> Building every ML concept from raw math and Python.  
> No shortcuts. No black boxes. One implementation at a time.

I'm an AI Engineer working professionally with LLMs, RAG systems, and agentic pipelines.  
This is what I do in my free time — open every library I use and rebuild it from the ground up.  
Not as an exercise. As a standard.

---

## What This Is

120 days. 120 projects. Every major concept in modern ML — implemented from scratch.

Each project includes:
- Full implementation in raw Python / NumPy
- Mathematical derivation and explanation
- Tests, visualizations, and documentation
- No sklearn, no PyTorch (until the PyTorch weeks), no shortcuts

**Curriculum revised at Day 45** (Oct 2026). The original plan ran to Day 90. After
finishing the transformer block I remapped the back half against a full AI-engineering
curriculum and extended to Day 120 — deeper coverage of pre-training, alignment,
inference optimization, agents, and a two-week computer vision block. What I cut and
why is at the bottom.

---

## Progress

**Current: Day 47 complete — Day 48 next**

| Phase | Topic | Days | Status |
|-------|-------|------|--------|
| **Month 1** | **Mathematical Foundations** | | |
| Week 1 | Linear Algebra | Days 1–5 | ✅ Complete |
| Week 2 | Probability & Statistics | Days 6–10 | ✅ Complete |
| Week 3 | Calculus & Optimization | Days 11–15 | ✅ Complete |
| Week 4 | Classical ML from Scratch | Days 16–20 | ✅ Complete |
| **Month 2** | **Advanced ML & Deep Learning** | | |
| Week 5 | Advanced Classical ML | Days 21–25 | ✅ Complete |
| Week 6 | Neural Networks from Scratch | Days 26–30 | ✅ Complete |
| Week 7 | Deep Learning with PyTorch | Days 31–35 | ✅ Complete |
| Week 8 | Sequence Models & Embeddings | Days 36–40 | ✅ Complete |
| **Month 3** | **Transformers & LLM Internals** | | |
| Week 9 | Transformers & Modern Architectures | Days 41–45 | ✅ Complete |
| Week 10 | Information Theory & Tokenization | Days 46–50 | 🔄 In Progress |
| Week 11 | Pre-training | Days 51–55 | 🔲 Upcoming |
| Week 12 | Fine-tuning & Alignment | Days 56–60 | 🔲 Upcoming |
| **Month 4** | **Inference & Production** | | |
| Week 13 | Inference Optimization | Days 61–65 | 🔲 Upcoming |
| Week 14 | Serving & Production ML | Days 66–70 | 🔲 Upcoming |
| Week 15 | Embeddings & Vector Search | Days 71–75 | 🔲 Upcoming |
| Week 16 | Retrieval-Augmented Generation | Days 76–80 | 🔲 Upcoming |
| **Month 5** | **LLM Engineering & Agents** | | |
| Week 17 | LLM Engineering I | Days 81–85 | 🔲 Upcoming |
| Week 18 | LLM Engineering II | Days 86–90 | 🔲 Upcoming |
| Week 19 | Agents I | Days 91–95 | 🔲 Upcoming |
| Week 20 | Agents II | Days 96–100 | 🔲 Upcoming |
| **Month 6** | **Vision, Multilingual & Capstone** | | |
| Week 21 | Computer Vision I | Days 101–105 | 🔲 Upcoming |
| Week 22 | Computer Vision II | Days 106–110 | 🔲 Upcoming |
| Week 23 | Multilingual & Multimodal | Days 111–115 | 🔲 Upcoming |
| Week 24 | Capstone | Days 116–120 | 🔲 Upcoming |

---

## Month 1 — Mathematical Foundations

### Week 1 — Linear Algebra

| Day | Project | Core Skill | Repo |
|-----|---------|------------|------|
| 1 | Matrix library from scratch | Linear algebra foundations | [→ repo](https://github.com/curiousafnan/Linear-Algebra-Implementation) |
| 2 | Vector transformations & eigenvectors | Geometry of linear algebra | [→ repo](https://github.com/curiousafnan/Vector-Transformations) |
| 3 | PCA from scratch using eigendecomposition | Dimensionality reduction theory | [→ repo](https://github.com/curiousafnan/PCA-From-Scratch) |
| 4 | SVD from scratch + image compression demo | Matrix factorization | [→ repo](https://github.com/curiousafnan/Singular-Value-Decomposition) |
| 5 | PageRank algorithm using linear algebra | Graph + linear algebra applied | [→ repo](https://github.com/curiousafnan/PageRank-Algorithm-Using-Linear-Algebra) |

### Week 2 — Probability & Statistics

| Day | Project | Core Skill | Repo |
|-----|---------|------------|------|
| 6 | Probability distributions simulator & visualizer | Stats foundations | [→ repo](https://github.com/curiousafnan/probability-distribution) |
| 7 | Central Limit Theorem — interactive visual proof | Statistical inference | [→ repo](https://github.com/curiousafnan/Central-Limit-Theorem---Interactive-Visual-Proof) |
| 8 | Bayesian inference engine from scratch | Bayes theorem applied | [→ repo](https://github.com/curiousafnan/Bayesian-Inference-Engine) |
| 9 | Hypothesis testing framework (t-test, chi-square) | Statistical testing | [→ repo](https://github.com/curiousafnan/Hypothesis-Testing-Framework) |
| 10 | Monte Carlo simulation — Pi estimation + finance | Probabilistic thinking | [→ repo](https://github.com/curiousafnan/Monte-Carlo-Simulation---Pi-Estimation) |

### Week 3 — Calculus & Optimization

| Day | Project | Core Skill | Repo |
|-----|---------|------------|------|
| 11 | Gradient descent visualizer (2D and 3D loss surfaces) | Optimization core | [→ repo](https://github.com/curiousafnan/Gradient-Descent-Visualizer) |
| 12 | Automatic differentiation engine from scratch | Backprop foundations | [→ repo](https://github.com/curiousafnan/Automatic-differentiation-engine-from-scratch) |
| 13 | Optimizers comparison — SGD, Momentum, Adam from scratch | Optimizer internals | [→ repo](https://github.com/curiousafnan/Optimizers-from-Scratch-SGD-Momentum-Adam) |
| 14 | Convexity & loss landscape explorer | Loss function geometry | [→ repo](https://github.com/curiousafnan/Convexity-Loss-Landscape-Explorer) |
| 15 | Newton's method vs gradient descent — visual comparison | Second order optimization | [→ repo](https://github.com/curiousafnan/Newton-s-Method-vs-Gradient-Descent) |

### Week 4 — Classical ML from Scratch

| Day | Project | Core Skill | Repo |
|-----|---------|------------|------|
| 16 | Linear regression from scratch with full math derivation | Regression | [→ repo](https://github.com/curiousafnan/Linear-Regression-from-Scratch) |
| 17 | Logistic regression + decision boundary visualizer | Classification | [→ repo](https://github.com/curiousafnan/Logistic-Regression-Decision-Boundary-Visualizer) |
| 18 | Decision tree from scratch (ID3/Gini) | Tree-based models | [→ repo](https://github.com/curiousafnan/Decision-Tree-from-Scratch-ID3-Gini-.git) |
| 19 | K-Means clustering from scratch + convergence visualizer | Unsupervised learning | [→ repo](https://github.com/curiousafnan/K-Means-Clustering-from-Scratch-Convergence-Visualizer.git) |
| 20 | Naive Bayes classifier from scratch on text data | Probabilistic classifiers | [→ repo](https://github.com/curiousafnan/Naive-Bayes-Classifier-from-Scratch-on-Text-Data) |

---

## Month 2 — Advanced ML & Deep Learning

### Week 5 — Advanced Classical ML

| Day | Project | Core Skill | Repo |
|-----|---------|------------|------|
| 21 | Random Forest from scratch (bagging + feature importance) | Ensemble methods | [→ repo](https://github.com/curiousafnan/Random-Forest-from-Scratch-Bagging-Feature-Importance-) |
| 22 | SVM from scratch with kernel trick visualized | Margin classifiers | [→ repo](https://github.com/curiousafnan/SVM-from-Scratch-with-Kernel-Trick-Visualized) |
| 23 | Gradient boosting from scratch (XGBoost concepts) | Boosting internals | [→ repo](https://github.com/curiousafnan/Gradient-Boosting-from-Scratch-XGBoost-Concepts-) |
| 24 | KNN from scratch + KD-tree optimization | Distance-based learning | [→ repo](https://github.com/curiousafnan/KNN-from-Scratch-KD-Tree-Optimization) |
| 25 | Gaussian Mixture Models + EM algorithm | Probabilistic clustering | [→ repo](https://github.com/curiousafnan/Gaussian-Mixture-Models-EM-Algorithm) |

### Week 6 — Neural Networks from Scratch

| Day | Project | Core Skill | Repo |
|-----|---------|------------|------|
| 26 | Single neuron — perceptron from scratch | Neural foundations | [→ repo](https://github.com/curiousafnan/Single-neuron-perceptron-from-scratch) |
| 27 | Multi-layer neural network from scratch (numpy only) | Forward pass | [→ repo](https://github.com/curiousafnan/Multi-Layer-Perceptron) |
| 28 | Backpropagation from scratch with visual computation graph | Backprop deeply | [→ repo](https://github.com/curiousafnan/Backpropagation-From-Scratch) |
| 29 | Activation functions deep dive — implement + compare all | Non-linearities | [→ repo](https://github.com/curiousafnan/Activation-functions-deep-dive) |
| 30 | Weight initialization strategies — why it matters visually | Training stability | [→ repo](https://github.com/curiousafnan/Weight-Initialization-Techniques.git) |

### Week 7 — Deep Learning with PyTorch

| Day | Project | Core Skill | Repo |
|-----|---------|------------|------|
| 31 | PyTorch from scratch mindset — rebuild Week 6 in PyTorch | Framework literacy | [→ repo](https://github.com/curiousafnan/PyTorch-from-Scratch-Mindset) |
| 32 | CNN from scratch in PyTorch on CIFAR-10 | Computer vision basics | [→ repo](https://github.com/curiousafnan/CNN-on-CIFAR-10) |
| 33 | BatchNorm, Dropout, Regularization — ablation study | Training techniques | [→ repo](https://github.com/curiousafnan/Implement-Batch-Norm-Dropout-and-L2-Regularization) |
| 34 | Learning rate schedulers — visual comparison project | LR tuning | [→ repo](https://github.com/curiousafnan/Learning-Rate-Schedulers) |
| 35 | Custom Dataset + DataLoader pipeline in PyTorch | ML engineering | [→ repo](https://github.com/curiousafnan/Custom-Dataset-DataLoader) |

### Week 8 — Sequence Models & Embeddings

| Day | Project | Core Skill | Repo |
|-----|---------|------------|------|
| 36 | Word2Vec from scratch (Skip-gram + CBOW) | Word embeddings | [→ repo](https://github.com/curiousafnan/Word2Vec-Skip-gram-CBOW-) |
| 37 | RNN from scratch — character-level language model | Sequence modelling | [→ repo](https://github.com/curiousafnan/RNN-character-level-language-model) |
| 38 | LSTM from scratch — long range dependency demo | Gating mechanisms | [→ repo](https://github.com/curiousafnan/LSTM-Long-range-dependency) |
| 39 | Attention mechanism from scratch — visual walkthrough | Attention internals | [→ repo](https://github.com/curiousafnan/Attention-Mechanism) |
| 40 | Positional encoding deep dive — why and how | Transformer building block | [→ repo](https://github.com/curiousafnan/Positional-encoding) |

---

## Month 3 — Transformers & LLM Internals

### Week 9 — Transformers & Modern Architectures ✅

| Day | Project | Core Skill | Repo |
|-----|---------|------------|------|
| 41 | Self-attention from scratch with visualization | Transformer core | [→ repo](https://github.com/curiousafnan/Self-Attention) |
| 42 | Multi-head attention from scratch (batched, no head loop) | Parallel attention | [→ repo](https://github.com/curiousafnan/Multi-Head-Attention.git) |
| 43–44 | Full encoder-decoder transformer (merged — one architecture) | Encoder + decoder + cross-attention | [→ repo](https://github.com/curiousafnan/Attention-is-All-You-Need.git) |
| 45 | Mini GPT — train a tiny language model from scratch | Full transformer | [→ repo](#) |

**Headline result:** on identical text (Alice in Wonderland, character-level) — RNN
reached loss 1.52 after 1000 epochs, LSTM 1.26 after 500, GPT 1.32 after **one**.
Adding a validation split then showed val loss turning upward after epoch 1
(epoch 7: train 0.42 / val 3.18) — ~9 parameters per character is memorization,
not learning. Recorded as the lesson of the week: a broken causal mask and a
memorizing model produce the same training curve.

### Week 10 — Information Theory & Tokenization 🔄

| Day | Project | Core Skill | Repo |
|-----|---------|------------|------|
| 46 | Entropy, cross-entropy, KL divergence, perplexity | Information theory | [→ repo](#) |
| 47 | Byte-level BPE tokenizer from scratch — merge loop & training | Tokenization internals | [→ repo](#) |
| 48 | Encode/decode, special tokens, GPT-2 regex pre-splitting | Tokenizer robustness | [→ repo](#) |
| 49 | WordPiece vs Unigram vs SentencePiece — compared | Subword algorithms | [→ repo](#) |
| 50 | Tokenizer fragmentation: English / Urdu / Pashto measured | Multilingual tokenization | [→ repo](#) |

### Week 11 — Pre-training

| Day | Project | Core Skill | Repo |
|-----|---------|------------|------|
| 51 | Data pipelines, mixed precision, gradient accumulation | Training at scale | [→ repo](#) |
| 52 | Retrain MiniGPT on BPE tokens — bits-per-character comparison | Tokenization impact | [→ repo](#) |
| 53 | KV cache from scratch — measure the generation speedup | Inference internals | [→ repo](#) |
| 54 | Scaling laws — Chinchilla, compute-optimal ratios | Training economics | [→ repo](#) |
| 55 | Mixture of Experts — build the gating network | Sparse architectures | [→ repo](#) |

### Week 12 — Fine-tuning & Alignment

| Day | Project | Core Skill | Repo |
|-----|---------|------------|------|
| 56 | Instruction tuning (SFT) with prompt loss masking | Supervised fine-tuning | [→ repo](#) |
| 57 | LoRA from scratch — low-rank decomposition + merge | Parameter-efficient tuning | [→ repo](#) |
| 58 | QLoRA + quantization — int8, int4, NF4, double quant | Memory-efficient tuning | [→ repo](#) |
| 59 | Reward modeling — preference pairs, Bradley-Terry | Preference learning | [→ repo](#) |
| 60 | DPO from scratch — derived from the RLHF objective | Alignment | [→ repo](#) |

---

## Month 4 — Inference & Production

### Week 13 — Inference Optimization

| Day | Project | Core Skill | Repo |
|-----|---------|------------|------|
| 61 | Quantization deep dive — PTQ, GPTQ, AWQ, outlier channels | Weight compression | [→ repo](#) |
| 62 | Speculative decoding — draft, verify, and the rejection rule | Latency reduction | [→ repo](#) |
| 63 | Flash Attention — tiling and online softmax | Memory-bound kernels | [→ repo](#) |
| 64 | Batching — continuous batching, paged attention | Throughput | [→ repo](#) |
| 65 | Benchmark everything — tokens/sec, TTFT, peak memory | Performance measurement | [→ repo](#) |

### Week 14 — Serving & Production ML

| Day | Project | Core Skill | Repo |
|-----|---------|------------|------|
| 66 | FastAPI serving — streaming, concurrency, backpressure | Model deployment | [→ repo](#) |
| 67 | Docker + deployment — multi-stage, pinned, non-root | DevOps for ML | [→ repo](#) |
| 68 | ML system design — business problem to deployed architecture | System design | [→ repo](#) |
| 69 | Data drift vs concept drift — detection from scratch | Production monitoring | [→ repo](#) |
| 70 | Feature store & training-serving skew | Pipeline correctness | [→ repo](#) |

### Week 15 — Embeddings & Vector Search

| Day | Project | Core Skill | Repo |
|-----|---------|------------|------|
| 71 | Bi-encoder vs cross-encoder — accuracy/latency crossover | Retrieval architectures | [→ repo](#) |
| 72 | Contrastive training — InfoNCE, temperature, hard negatives | Embedding training | [→ repo](#) |
| 73 | Vector search from scratch — brute force → IVF → HNSW | Index internals | [→ repo](#) |
| 74 | Metric learning — cosine vs dot vs L2, triplet loss | Distance metrics | [→ repo](#) |
| 75 | Benchmark against FAISS and a hosted vector DB | Recall/latency frontier | [→ repo](#) |

### Week 16 — Retrieval-Augmented Generation

| Day | Project | Core Skill | Repo |
|-----|---------|------------|------|
| 76 | Naive RAG end to end — the baseline to beat | Retrieval systems | [→ repo](#) |
| 77 | Chunking — fixed, overlap, semantic, hierarchical | Context construction | [→ repo](#) |
| 78 | Hybrid search — BM25 from scratch + reciprocal rank fusion | Sparse + dense | [→ repo](#) |
| 79 | Reranking + query rewriting (decomposition, HyDE) | Retrieval quality | [→ repo](#) |
| 80 | RAG evaluation — recall@k, nDCG, faithfulness, judge validation | Measurement | [→ repo](#) |

---

## Month 5 — LLM Engineering & Agents

### Week 17 — LLM Engineering I

| Day | Project | Core Skill | Repo |
|-----|---------|------------|------|
| 81 | Prompt engineering as code — versioned, tested, scored | Systematic prompting | [→ repo](#) |
| 82 | Few-shot, chain-of-thought, self-consistency, tree-of-thought | Reasoning scaffolds | [→ repo](#) |
| 83 | Structured outputs — JSON schema to constrained decoding | Guaranteed parseability | [→ repo](#) |
| 84 | Context engineering — token budgets, compaction, lost-in-the-middle | Window management | [→ repo](#) |
| 85 | LLM evaluation harness — rubrics, pairwise, judge agreement | Evaluation | [→ repo](#) |

### Week 18 — LLM Engineering II

| Day | Project | Core Skill | Repo |
|-----|---------|------------|------|
| 86 | Caching — exact, semantic, prefix/prompt caching | Cost & latency | [→ repo](#) |
| 87 | Cost optimization, rate limiting, fallback chains | Reliability | [→ repo](#) |
| 88 | Guardrails — injection defense, PII redaction, attack suite | LLM security | [→ repo](#) |
| 89 | Observability — tracing, token accounting, latency budgets | Production visibility | [→ repo](#) |
| 90 | **Production LLM application** — Weeks 16–18 combined, deployed | Full stack AI | [→ repo](#) |

### Week 19 — Agents I

| Day | Project | Core Skill | Repo |
|-----|---------|------------|------|
| 91 | The agent loop from scratch — no framework | Agentic AI | [→ repo](#) |
| 92 | Tool interface design — measured against bad definitions | Tool design | [→ repo](#) |
| 93 | Function calling — parallel calls, streaming, model-facing errors | Production mechanics | [→ repo](#) |
| 94 | MCP server — JSON-RPC 2.0, stdio and HTTP transports | Protocol implementation | [→ repo](#) |
| 95 | MCP client — discovery, routing, lifecycle | Protocol integration | [→ repo](#) |

### Week 20 — Agents II

| Day | Project | Core Skill | Repo |
|-----|---------|------------|------|
| 96 | Agent memory — working, episodic, semantic, context paging | Long-horizon agents | [→ repo](#) |
| 97 | Hybrid memory — vector + graph + KV under one interface | Memory architecture | [→ repo](#) |
| 98 | Planning — plan-and-execute, ReWOO, vs ReAct | Agent planning | [→ repo](#) |
| 99 | Reflexion and self-refine — including where it makes things worse | Self-correction | [→ repo](#) |
| 100 | Workflow patterns — and when an agent is the wrong answer | Architectural judgment | [→ repo](#) |

---

## Month 6 — Vision, Multilingual & Capstone

### Week 21 — Computer Vision I

| Day | Project | Core Skill | Repo |
|-----|---------|------------|------|
| 101 | Convolutions from scratch — im2col + GEMM, forward and backward | Conv internals | [→ repo](#) |
| 102 | ResNet from scratch — plain-18 as the control | Residual learning | [→ repo](#) |
| 103 | Transfer learning — linear probe vs full vs gradual unfreezing | Fine-tuning vision | [→ repo](#) |
| 104 | Chest X-ray classifier — ROC/PR-AUC, calibration, Grad-CAM | Medical imaging | [→ repo](#) |
| 105 | Object detection — YOLO-style head, IoU, NMS, mAP | Detection | [→ repo](#) |

### Week 22 — Computer Vision II

| Day | Project | Core Skill | Repo |
|-----|---------|------------|------|
| 106 | Semantic segmentation — U-Net, with skip-connection ablation | Dense prediction | [→ repo](#) |
| 107 | Vision Transformer — patch embedding, CLS token, vs ResNet | Attention on images | [→ repo](#) |
| 108 | CLIP — dual encoder, contrastive loss, zero-shot classification | Multimodal learning | [→ repo](#) |
| 109 | OCR fundamentals — CTC loss, CER/WER, detection + recognition | Text recognition | [→ repo](#) |
| 110 | Document understanding — layout, reading order, table structure | Document AI | [→ repo](#) |

### Week 23 — Multilingual & Multimodal

| Day | Project | Core Skill | Repo |
|-----|---------|------------|------|
| 111 | Multilingual NLP — cross-lingual transfer vs tokenizer fertility | Low-resource NLP | [→ repo](#) |
| 112 | Urdu/English sentiment — including Roman Urdu and code-switching | Applied multilingual | [→ repo](#) |
| 113 | ColPali — vision-native document retrieval, OCR bypassed | Late interaction | [→ repo](#) |
| 114 | Multimodal RAG — cross-modal retrieval and ranking | Unified retrieval | [→ repo](#) |
| 115 | Pashto/Urdu document pipeline — measured feasibility verdict | Decision with numbers | [→ repo](#) |

### Week 24 — Capstone

| Days | Project | Core Skill | Repo |
|------|---------|------------|------|
| 116–120 | One substantial build, decided at Day 115 | Full ML lifecycle | [→ repo](#) |

Candidates: RAG over Pakistani legal/medical documents · Pashto/Urdu document
understanding · Urdu/English sentiment at depth. Day 115's measurements decide it.

---

## Parallel Tracks

The daily builds are the learning. These run alongside and are what the learning is for.

| Track | Cadence | What |
|---|---|---|
| **Papers** | 1 every 6 weeks | Read cold from the PDF, reimplement with no tutorial open. LoRA → DPO → ResNet/CLIP |
| **Models** | 1 per week | A HuggingFace model dissected — read `config.json`, hand-count the FFN/attention parameter split, measure Urdu and Pashto tokens-per-word |
| **Shipped projects** | 1 per month | Open source, real users, a Pakistani problem. Not toys |
| **DSA** | 2 problems per week | Interview maintenance |

**Shipped means:** deployed where a stranger can use it, or on HuggingFace with a
real model/dataset card and reproducible numbers; open source; at least one user
who isn't me; something fixed that broke in the wild; and **still running three
months later**.

---

## Rules

The challenge only means something if the rules hold. The full set lives in the
project docs; the load-bearing ones:

- **From scratch is defined per day.** The day's concept is mine to implement; anything
  an earlier week earned becomes a primitive. If the day's title appears as a library
  call, it's cheating. `nn.MultiheadAttention` on Day 42 is cheating — on Day 107 it's
  fine, because Day 42 paid for it. Exceptions get declared in writing.
- **Concept before code.** No editor until I can state the problem, why the obvious
  approach fails, the shape of the fix, and how I'd know it worked.
- **Predict before running.** Expected shapes and expected loss at initialization written
  down first. Cross-entropy over V classes starts near `ln(V)` — a number I didn't
  predict teaches me nothing.
- **Validation splits on anything that trains.** Train loss alone is not evidence. Day 45
  taught this the expensive way.
- **Engineered tests, not generic ones.** Every component gets an input where a wrong
  implementation visibly disagrees with a right one. The bugs that crash are cheap;
  the ones that return plausible numbers are not.
- **3 seeds and a stated noise floor** on any comparison. A 3% improvement inside 5%
  seed variance is not an improvement.
- **`learnings.md` records what broke.** A repo of flawless commits is a repo nobody
  believes.

---

## What I Cut, and Why

The original 90-day plan covered more topics more thinly. Revising at Day 45 meant
choosing depth, with the priority being employable engineering skill:

| Cut | Reason |
|---|---|
| RL (Q-learning, bandits) | Kept only the DPO/PPO coverage in Week 12, which is where alignment actually uses it |
| Generative models (VAE, GAN, DDPM) | Genuinely interesting, not job-relevant for me right now. DDPM stays on the paper list |
| GNNs | Narrow applicability relative to the two weeks it would cost |
| Standalone "DSA applied to ML" week | Moved to the parallel track — 2 problems a week, continuously, beats one burst |
| A/B testing, Kafka streaming, distributed training | Partly absorbed into Weeks 14 and 11; the rest is reading, not building |
| MNIST in pure numpy | A Week 6 checkpoint that's now well below current level |
| Speech & audio | 3 reserve days held back, to be used only if a voice project appears at work |

**Added instead:** a full two-week computer vision block, proper pre-training and
inference-optimization weeks, MCP server and client, and a multilingual block aimed
at Pashto and Urdu — which is where I think I can do work nobody else is doing.

---

## Why From Scratch?

Most engineers know *what* a transformer does.  
Fewer know *why* it works.  
Almost nobody has written every layer by hand.

Building from scratch forces you to understand — not memorize.  
Every library I use professionally, I've rebuilt. That's the standard.

---

## Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/muhammad-afnan-3272a2218)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://instagram.com/m.r_afnan)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/curiousafnan)

*For the curious people. Always open.*
