---
title: "BT^2: Backward-compatible Training with Basis Transformation"
collection: publications
permalink: /publication/BT2
excerpt: '**Yifei Zhou**\*, Zilu Li\*, Abhinav Shrivastava, Hengshuang Zhao, Antonio Torralba, Taipeng Tian, Ser-Nam Lim'
venue: 'ICCV 2023'
date: 2023-05-17
---
[paper](https://arxiv.org/abs/2211.03989)
![dimension_reduction](https://user-images.githubusercontent.com/83000332/200725681-2ecb9692-b9e1-4205-820e-a952d265bffd.png)


# abstract:
Modern retrieval system often requires recomputing the representation of every piece of data in the gallery when updating to a better representation model. This process is known as backfilling and can be especially costly in the real world where the gallery often contains billions of samples. Recently, researchers have proposed the idea of Backward Compatible Training (BCT) where the new representation model can be trained with an auxiliary loss to make it backward compatible with the old representation. In this way, the new representation can be directly compared with the old representation, in principle avoiding the need for any backfilling. However, followup work shows that there is an inherent tradeoff where a backward compatible representation model cannot simultaneously maintain the performance of the new model itself. This paper reports our ``not-so-surprising'' finding that adding extra dimensions to the representation can help here. However, we also found that naively increasing the dimension of the representation did not work. To deal with this, we propose Backward-compatible Training with a novel Basis Transformation (BT^2). A basis transformation (BT) is basically a learnable set of parameters that applies an orthonormal transformation. Such a transformation possesses an important property whereby the original information contained in its input is retained in its output. We show in this paper how a BT can be utilized to add only the necessary amount of additional dimensions. We empirically verify the advantage of BT^2 over other state-of-the-art methods in a wide range of settings. We then further extend BT^2 to other challenging yet more practical settings, including significant change in model architecture (CNN to Transformers), modality change, and even a series of updates in the model architecture mimicking the evolution of deep learning models in the past decade. 
