---
title: "PSWEET-RL: Training Multi-Turn LLM Agents on Collaborative Reasoning Tasks"
collection: publications
permalink: /publication/sweetrl
excerpt: '**Yifei Zhou**, Song Jiang\*, Yuandong Tian, Sergey Levine, Sainbayar Sukhbaatar, Xian Li
venue: 'Pre-print'
date: 2025-3-24
---
[paper](https://arxiv.org/abs/2503.15478)
[code](https://github.com/facebookresearch/sweet_rl)
[data](https://huggingface.co/datasets/facebook/collaborative_agent_bench)

# abstract:
Large language model (LLM) agents need to perform multi-turn interactions in real-world tasks. However, existing multi-turn RL algorithms for optimizing LLM agents fail to perform effective credit assignment over multiple turns while leveraging the generalization capabilities of LLMs and it remains unclear how to develop such algorithms. To study this, we first introduce a new benchmark, ColBench, where an LLM agent interacts with a human collaborator over multiple turns to solve realistic tasks in backend programming and frontend design. Building on this benchmark, we propose a novel RL algorithm, SWEET-RL (RL with Step-WisE Evaluation from Training-time information), that uses a carefully designed optimization objective to train a critic model with access to additional training-time information. The critic provides step-level rewards for improving the policy model. Our experiments demonstrate that SWEET-RL achieves a 6% absolute improvement in success and win rates on ColBench compared to other state-of-the-art multi-turn RL algorithms, enabling Llama-3.1-8B to match or exceed the performance of GPT4-o in realistic collaborative content creation.
