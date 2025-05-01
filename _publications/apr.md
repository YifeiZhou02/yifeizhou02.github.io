---
title: "Learning Adaptive Parallel Reasoning
with Language Models"
collection: publications
permalink: /publication/apr
excerpt: 'Jiayi Pan\*, Xiuyu Li\*, Long Lian\*, Charlie Victor Snell, **Yifei Zhou**, Adam Yala, Trevor Darrell, Kurt Keutzer, Alane Suhr'
venue: 'Preprint'
date: 2025-4-21
---
[paper](https://arxiv.org/abs/2504.15466)
[code](https://github.com/Parallel-Reasoning/APR?tab=readme-ov-file)

# abstract:
Scaling inference-time computation has substantially improved the reasoning capabilities of language models. However, existing methods have significant limitations: serialized chain-of-thought approaches generate overly long outputs, leading to increased latency and exhausted context windows, while parallel methods such as self-consistency suffer from insufficient coordination, resulting in redundant computations and limited performance gains. To address these shortcomings, we propose Adaptive Parallel Reasoning (APR), a novel reasoning framework that enables language models to orchestrate both serialized and parallel computations end-to-end. APR generalizes existing reasoning methods by enabling adaptive multi-threaded inference using spawn() and join() operations. A key innovation is our end-to-end reinforcement learning strategy, optimizing both parent and child inference threads to enhance task success rate without requiring predefined reasoning structures. Experiments on the Countdown reasoning task demonstrate significant benefits of APR: (1) higher performance within the same context window (83.4% vs. 60.0% at 4k context); (2) superior scalability with increased computation (80.1% vs. 66.6% at 20k total tokens); (3) improved accuracy at equivalent latency (75.2% vs. 57.3% at approximately 5,000ms). APR represents a step towards enabling language models to autonomously optimize their reasoning processes through adaptive allocation of computation.
