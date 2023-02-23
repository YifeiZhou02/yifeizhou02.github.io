---
title: "Distribution Normalization: An \"Effortless\" Test-Time Augmentation for Contrastively Learned Visual-language Models"
collection: publications
permalink: /publication/distribution_normaization
excerpt: '**Yifei Zhou**\*, Juntao Ren\*, Fengyu Li\*, Ramin Zabih, Ser-Nam Lim'
venue: 'Preprint'
date: 2023-06-17
---
[paper](https://arxiv.org/abs/2302.11084)
![intro_graph](https://user-images.githubusercontent.com/83000332/220809765-4245b37b-fd51-434e-8d06-e6c5b8e4f1c1.png)




# abstract:
Advances in the field of visual-language contrastive learning have made it possible for many downstream applications to be carried out efficiently and accurately by simply taking the dot product between image and text representations. One of the most representative approaches proposed recently known as CLIP has quickly garnered widespread adoption due to its effectiveness. CLIP is trained with an InfoNCE loss that takes into account both positive and negative samples to help learn a much more robust representation space. This paper however reveals that the common downstream practice of taking a dot product is only a zeroth-order approximation of the optimization goal, resulting in a loss of information during test-time. Intuitively, since the model has been optimized based on the InfoNCE loss, test-time procedures should ideally also be in alignment. The question lies in how one can retrieve any semblance of negative samples information during inference. We propose Distribution Normalization (DN), where we approximate the mean representation of a batch of test samples and use such a mean to represent what would be analogous to negative samples in the InfoNCE loss. DN requires no retraining or fine-tuning and can be effortlessly applied during inference. Extensive experiments on a wide variety of downstream tasks exhibit a clear advantage of DN over the dot product.
