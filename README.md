# Cetin Furkan Cakin

## Systems Engineer & AI Innovator

A results-oriented systems engineer and AI researcher specializing in ultra-low-latency architectures, kernel-level optimizations, and next-generation machine intelligence. I architect production-grade solutions for high-frequency trading (HFT) infrastructures, custom AI accelerators, and performant data pipelines. My engineering philosophy centers on bridging theoretical rigor—rooted in measure-theoretic probability, Riemannian geometry, and bilevel optimization—with hands-on implementations in C23, leveraging Intel oneAPI for heterogeneous computing and math kernels like Intel MKL for tensor operations.

Expertise spans parsing terabit-scale binary protocols (e.g., ITCH 5.0) for real-time order matching, developing adaptive tokenizers that preserve semantic fidelity across multilingual corpora, and engineering Vulkan-accelerated models that bypass framework overheads for sub-millisecond inference.

## Core Competencies

- **Languages & Paradigms**: C (C23 with intrinsics for AVX-512), Python (for prototyping differentiable primitives)
- **Systems & Acceleration**: Linux kernel extensions, Vulkan (SPIR-V shaders, timeline semaphores), Wayland compositing, PostgreSQL (sharded schemas with pgvector), D-Bus (async IPC), io_uring (kernel bypass), Intel oneAPI (SYCL for CPU/GPU dispatch), math libraries (MKL for BLAS/LAPACK, Eigen for tensor algebra)
- **Advanced Data Structures & Algorithms**: Persistent segment trees for versioned query logs, wavelet trees for compressed suffix indexing, cuckoo hashing with linear probing for cache-oblivious lookups, HyperLogLog++ for cardinality estimation in streaming pipelines, treaps for priority-based order books, skip lists with probabilistic merging for concurrent access, Fenwick trees extended to multidimensional range queries
- **AI Architectures & Foundations**: Adaptive tokenizers (Unigram with subword regularization, TokenAdapt for dynamic entropy adaptation), models (Qwen-72B for multilingual reasoning, DinoV3 for self-supervised vision embeddings), modern paradigms (State Space Models like Mamba-2 with selective scan mechanisms, RWKV-7 for linear recurrent inference, Mixture of Routers for sparse gating in hybrid MoE), mathematical underpinnings (PAC-Bayesian bounds, variational inference over dynamical systems, online convex optimization for meta-adaptation)
- **Optimization Domains**: Microarchitectural tuning (out-of-order execution, uop fusion on Intel Tiger Lake), hardware-software co-design (SIMD vectorization, cache prefetching), low-latency networking (UDP multicast with DPDK)

## Featured Projects

- **ITCH 5.0 Limit Order Book Engine**: A C23-based, lock-free matching engine parsing NASDAQ's binary multicast feed at line rate, supporting add/modify/cancel operations, auction sequencing, and imbalance dissemination. Integrates a zero-copy UDP server for sub-microsecond dissemination, validated against reference datasets with 100% fidelity. Emphasizes branchless decision trees and SIMD-accelerated price-time priority queues.

- **Secure E-Commerce Transaction Backend**: PostgreSQL-backed C service for high-throughput user lifecycle management, featuring bcrypt-augmented authentication, session tokens with HMAC validation, and ACID-compliant cart reconciliation. Optimized with B-tree indexing for O(log n) username resolution and direct foreign-key traversal, stress-tested under 10k concurrent curls for 99.99% uptime.

- **Neural Tokenizer Suite**: From-scratch implementations of entropy-minimizing unigram models and TokenAdapt variants, engineered to retain case, diacritics, and elongation-based sentiment cues in tokenized sequences. Supports Qwen integration for fine-tuned embeddings, with extensions to DinoV3 for multimodal token fusion in vision-language tasks.

- **NebulaBar: Vulkan-Wayland Status Daemon**: A minimalist, io_uring-driven menu bar daemon rendering notification overlays, network telemetry, and Bluetooth state via Vulkan pipelines. Achieves 60 FPS at <1% CPU via descriptor pooling and async D-Bus polling, deployable as a systemd service for persistent Wayland sessions.

## Research Trajectory & Horizons

Currently engineering a bespoke Linux kernel module for HPC-grade exchange APIs, incorporating eBPF hooks for programmable packet inspection and oneAPI-accelerated tensor cores for on-the-fly risk computation. Deepening explorations in post-transformer paradigms: implementing Mamba-2's hardware-aware state expansions for O(1) sequence modeling, RWKV dialect variants with rotary positional encodings for infinite-context extrapolation, and latent reasoning circuits using recurrent expert mixtures—silent loops that evolve internal states via process-supervised rewards, bypassing token-level verbosity for emergent code synthesis and agentic planning.

Bridging to neuro-symbolic hybrids, I'm prototyping differentiable routers in Qwen backbones augmented with DinoV3 priors, enabling test-time adaptation through bilevel gradients and measure-theoretic priors for uncertainty quantification. Future ambitions include variational diffusion on manifolds for generative priors in BCI simulations, targeting O-1 visa pathways to US labs.

Aspiring to principal research roles at frontiers like xAI or Neuralink, I prioritize remote collaborations on open-source kernels, sparse AI accelerators, or fintech primitives. Eager for visa-sponsored relocation; let's architect the next leap in scalable intelligence.

## Reach Out

- **GitHub**: Cetin-Furkan  
- **LinkedIn**: https://github.com/Cetin-Furkan
- **Email**: c.furkan.cakin@gmail.com  

Open to dissecting SPIR-V pipelines or debating SSM stability—ping me. 🔬
