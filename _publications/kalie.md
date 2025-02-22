---
title: "KALIE: Fine-Tuning Vision-Language Models for Open-World Manipulation without Robot Data"
collection: publications
permalink: /publication/kalie
excerpt: 'Grace Tang\*, Swetha Rajkumar\*, **Yifei Zhou**, Homer Rich Walke, Sergey Levine, Kuan Fang'
venue: 'ICRA 2025'
date: 2024-10-18
---
[website](https://kalie-vlm.github.io/)
[paper](https://arxiv.org/abs/2409.14066)

# abstract:
Building generalist robotic systems involves effectively endowing robots the capabilities to handle novel objects in an open-world setting. Inspired by the advances of large pre-trained models, we propose Keypoint Affordance Learning from Imagined Environments (KALIE), which adapts pre-trained Vision Language Models (VLMs) for robotic control in a scalable manner. Instead of directly producing motor commands, KALIE controls the robot by predicting point-based affordance representations based on natural language instructions and visual observations of the scene. The VLM is trained on 2D images with affordances labeled by humans, bypassing the need for training data collected on robotic systems. Through an affordance-aware data synthesis pipeline, KALIE automatically creates massive high-quality training data based on limited example data manually collected by humans. We demonstrate that KALIE can learn to robustly solve new manipulation tasks with unseen objects given only 50 example data points. Compared to baselines using pre-trained VLMs, our approach consistently achieves superior performance.
