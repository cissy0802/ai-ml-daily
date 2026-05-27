# Topics Roadmap

源是仓库中的文件本身（`ls *-{day,week,book,issue}*.html`）。本文件只是主题查找表：N → 主题。超过现有编号时 routine 会 append 新主题。

**定位**：学术 / 概念 / 机制。讲「X 是什么、为什么发明、怎么工作」。**不教工程 tactics**——那些归 super-individual-weekly。

## 已生成（Day 1-9）
- Day 1: LLM 基础 — Transformer 架构, Attention 机制, Tokenization, 位置编码
- Day 2: 预训练与微调 — Pre-training, SFT, RLHF, DPO
- Day 3: Prompt Engineering — Zero/Few-shot, CoT, ReAct, Self-Consistency
- Day 4: RAG 体系 — Embedding, Vector DB, Retrieval 策略, Re-ranking
- Day 5: Agent 架构 — ReAct Agent, Plan-and-Execute, Reflexion, AutoGPT
- Day 6: Tool Use — Function Calling, MCP 协议, Tool 选择策略, Sandboxing
- Day 7: Multi-Agent 系统 — AutoGen, CrewAI, 角色分工, 协作协议
- Day 8: Context 工程 — Context Window, Context Caching, Compression, Memory 管理
- Day 9: 推理优化 — KV Cache, Speculative Decoding, Continuous Batching, Quantization

## Phase 1 — 模型架构与训练数学
- Day 10: Loss 函数 & Optimization — MSE, CrossEntropy, AdamW, LR Schedule, Gradient Clipping
- Day 11: Tokenization 深度 — BPE / WordPiece / SentencePiece, Vocab 权衡, UTF-8 边界
- Day 12: Attention 变种 — MHA / GQA / MQA / Sliding Window / Flash Attention 数学
- Day 13: 位置编码深入 — Absolute / Sinusoidal / RoPE / ALiBi, 长 context 数学
- Day 14: Scaling Laws — Chinchilla, Compute-optimal, Emergent abilities
- Day 15: 评估与基准 — MMLU, HumanEval, MT-Bench, LLM-as-Judge 数学

## Phase 2 — 经典 ML 与深度学习
- Day 16: 经典 ML 算法 — 线性回归, 逻辑回归, 决策树, 随机森林, SVM
- Day 17: 深度学习基础 — 反向传播, 梯度下降, 激活函数, 正则化
- Day 18: CNN 与视觉 — 卷积原理, ResNet, ViT, CLIP
- Day 19: RNN 与序列 — LSTM, GRU, Seq2Seq, Attention 起源
- Day 20: 生成模型 — GAN, VAE, Diffusion Models, Flow Matching
- Day 21: 强化学习 — Q-Learning, Policy Gradient, PPO, Actor-Critic
- Day 22: 语义搜索 — Dense Retrieval, BM25, Hybrid Search, HNSW
- Day 23: 多模态 — VLM, Audio LLM, 视频理解, Embodied AI
- Day 24: 编码模型 — BERT, RoBERTa, Sentence Transformers, ColBERT
- Day 25: 训练基础设施 — 分布式训练, FSDP, ZeRO, Megatron-LM

## Phase 3 — 前沿研究方向
- Day 26: Alignment 数学 — RLHF 数学, Reward Model, Constitutional AI, DPO loss
- Day 27: 可解释性 — Mechanistic Interpretability, Sparse Autoencoders, Feature Circuits, Probing
- Day 28: 推理模型 — o1 架构, CoT 推理, Self-Verification, Best-of-N
- Day 29: 数据工程 — Synthetic Data, Data Curation, Deduplication, Quality Filtering
- Day 30: 嵌入与表示 — Word2Vec, GloVe, Contrastive Learning, Matryoshka Embeddings
- Day 31: 模型压缩 — Distillation, Pruning, LoRA, QLoRA, Quantization 数学
- Day 32: 激活函数与归一化 — ReLU/GELU/SwiGLU, BatchNorm/LayerNorm/RMSNorm
- Day 33: 概率与信息论基础 — KL Divergence, Entropy, Mutual Information, ELBO
- Day 34: 前沿架构 — MoE, Mamba/SSM, Long Context, State Space Models
