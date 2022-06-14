---
title: "Improve Discourse Dependency Parsing with Contextualized Representations"
collection: publications
permalink: /publication/discourse_parsing
excerpt: Propose to improve discourse dependency parsing with EDU-level contextualization.
venue: NAACL 2022 (findings)
date: 2022-7
author: Yifei Zhou and Yansong Feng
paperurl: 'https://arxiv.org/abs/2205.02090'
---
[code](https://github.com/YifeiZhou02/Improve-Discourse-Dependency-Parsing-with-Contextualized-Representations)

![DDP model overview](https://user-images.githubusercontent.com/83000332/165659676-c641cc42-6500-44ce-afec-b64cfd8192d9.png)

# abstract:
Recent works show that discourse analysis benefits from modeling  intra- and inter-sentential levels separately, where proper representations for text units of different granularities are desired to capture both the meaning of text units and their relations to the context. In this paper, we propose to take advantage of transformers to encode  contextualized representations 
of units of different levels to dynamically capture the information required for discourse dependency analysis on intra- and inter-sentential levels. Motivated by the observation of writing patterns commonly shared across articles, we propose a novel method that treats discourse relation identification as a sequence labelling task, which takes advantage of structural information from the context of extracted discourse trees, and  substantially outperforms traditional direct-classification methods. Experiments show that our model achieves state-of-the-art results on both English and Chinese datasets. 
