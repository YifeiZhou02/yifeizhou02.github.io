---
title: "GAPX: Generalized Autoregressive Paraphrase-identification X"
collection: publications
permalink: /publication/GAPX
excerpt: '**Yifei Zhou**, Renyu Li, Hayden Housen, and Sernam Lim'
venue: 'NeurIPS 2022'
date: 2022-07-17
---
[paper](https://arxiv.org/abs/2210.01979)
[code](https://github.com/YifeiZhou02/generalized_paraphrase_identification)
![Canvas 1](https://user-images.githubusercontent.com/83000332/173618717-570f697c-2671-41aa-96da-1459fc627332.png)

# abstract:
Paraphrase Identification is a fundamental task in Natural Language Processing. While much progress has been made in the field, the performance of many state-of-the-art models often suffer from distribution shift during inference time. We verify that a major source of this performance drop comes from biases introduced by negative examples. To overcome these biases, we propose in this paper to train two separate models, one that only utilizes the positive pairs and the other the negative pairs. This enables us the option of deciding how much to utilize the negative model, for which we introduce a perplexity based out-of-distribution metric that we show can effectively and automatically determine how much weight it should be given during inference. We support our findings with strong empirical results.
