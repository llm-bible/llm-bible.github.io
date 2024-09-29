---
layout: publication
title: "Attention Guided Semantic Relationship Parsing For Visual Question Answering"
authors: Farazi Moshiur, Khan Salman, Barnes Nick
conference: "Arxiv"
year: 2020
bibkey: farazi2020attention
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.01725"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Multimodal Models']
---
Humans explain inter-object relationships with semantic labels that demonstrate a high-level understanding required to perform complex Vision-Language tasks such as Visual Question Answering (VQA). However existing VQA models represent relationships as a combination of object-level visual features which constrain a model to express interactions between objects in a single domain while the model is trying to solve a multi-modal task. In this paper we propose a general purpose semantic relationship parser which generates a semantic feature vector for each subject-predicate-object triplet in an image and a Mutual and Self Attention (MSA) mechanism that learns to identify relationship triplets that are important to answer the given question. To motivate the significance of semantic relationships we show an oracle setting with ground-truth relationship triplets where our model achieves a ~2537; accuracy gain over the closest state-of-the-art model on the challenging GQA dataset. Further with our semantic parser we show that our model outperforms other comparable approaches on VQA and GQA datasets.
