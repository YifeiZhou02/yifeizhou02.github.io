---
title: "Autonomous Evaluation and Refinement of Digital Agents"
collection: publications
permalink: /publication/agenteval
excerpt: 'Jiayi Pan, Yichi Zhang, Nicolas Tomlin, Yifei Zhou, Sergey Levine, Alane Suhr'
venue: 'Preprint'
date: 2024-4-10
---
[paper](https://arxiv.org/abs/2404.06474)


[code](https://github.com/Berkeley-NLP/Agent-Eval-Refine)

# abstract:
We show that domain-general automatic evaluators can significantly improve the performance of agents for web navigation and device control. 
We experiment with multiple evaluation models that trade off between inference cost, modularity of design, and accuracy. 
We validate the performance of these models in several popular benchmarks for digital agents, finding between 74.4 and 92.9% agreement with oracle evaluation metrics.
Finally, we use these evaluators to improve the performance of existing agents via fine-tuning and inference-time guidance. Without any additional
supervision, we improve state-of-the-art performance by 29% on the popular benchmark WebArena, and achieve a 75% relative improvement in
a challenging domain transfer scenario.
