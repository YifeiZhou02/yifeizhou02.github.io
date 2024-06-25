---
title: "Aligning Large Language Models with Representation Editing: A Control Perspective"
collection: publications
permalink: /publication/controlLM
excerpt: 'Lingkai Kong\*, Haorui Wang\*, Wenhao Mu\*, Yuanqi Du, Yuchen Zhuang, **Yifei Zhou**, Yue Song, Rongzhi Zhang, Kai Wang, Chao Zhang'
venue: 'Preprint'
date: 2024-6-11
---
[paper](https://arxiv.org/abs/2406.11896)

# abstract:
Aligning large language models (LLMs) with human objectives is crucial for real-world applications. However, fine-tuning LLMs for alignment often suffers from unstable training and requires substantial computing resources. Test-time alignment techniques, such as prompting and guided decoding, do not modify the underlying model, and their performance remains dependent on the original model's capabilities. To address these challenges, we propose aligning LLMs through representation editing. The core of our method is to view a pre-trained autoregressive LLM as a discrete-time stochastic dynamical system. To achieve alignment for specific objectives, we introduce external control signals into the state space of this language dynamical system. We train a value function directly on the hidden states according to the Bellman equation, enabling gradient-based optimization to obtain the optimal control signals at test time. Our experiments demonstrate that our method outperforms existing test-time alignment techniques while requiring significantly fewer resources compared to fine-tuning methods.
