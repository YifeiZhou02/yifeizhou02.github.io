---
title: "Digi-Q: Learning VLM Q-Value Functions for Training Device-Control Agents"
collection: publications
permalink: /publication/digiq
excerpt: 'Hao Bai\*, **Yifei Zhou**\*, Erran Li, Sergey Levine, Aviral Kumar'
venue: 'ICLR 2025'
date: 2025-2-21
---
[paper](https://digirl-agent.github.io/DigiQ-agent.github.io/website/data/digiq.pdf)
[website](https://digirl-agent.github.io/DigiQ-agent.github.io/)
[code](https://github.com/DigiRL-agent/digiq)

# abstract:
While most paradigms for building foundation model agents rely on prompting or fine-tuning on demonstrations, it is not sufficient in dynamic environments (e.g., mobile device control). On-policy reinforcement learning (RL) should address these limitations, but collecting actual rollouts in an environment is often undesirable when using truly open-ended agentic tasks such as mobile device, where simulation is a bottleneck. In such scenarios, an offline method for policy improvement that utilizes a trained value-function for training the policy is much more practical. In this paper, we develop a scalable value-based offline RL approach called Digi-Q to train VLM agents for device control entirely from static data. The key idea in Digi-Q is to train a value function using offline temporal-difference (TD) learning. We show that this can be done by fine-tuning a Q-function on top of frozen, intermediate-layer features of a VLM rather than fine-tuning the whole VLM itself, which saves us compute and enhances training stability. To make the VLM features amenable for representing the value function, we need to employ an initial phase of fine-tuning to amplify coverage over actionable information critical for Q-functions. Once trained, we use this value function alongside a best-of-N policy extraction operator that imitates the best action out of multiple candidate actions from the current policy as ranked by the value function, enabling policy improvement without ever needing to use the simulator. Digi-Q outperforms several prior methods on user-scale device control tasks in Android-in-the-Wild, attaining 9.9% improvement over prior best-performing method.
