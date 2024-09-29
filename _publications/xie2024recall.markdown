---
layout: publication
title: Recall Membership Inference Via Relative Conditional Log-likelihoods
authors: Xie Roy, Wang Junlin, Huang Ruomin, Zhang Minxing, Ge Rong, Pei Jian, Gong Neil Zhenqiang, Dhingra Bhuwan
conference: "Arxiv"
year: 2024
bibkey: xie2024recall
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.15968"}
tags: ['Ethics And Bias', 'Language Modeling', 'Pretraining Methods', 'RAG', 'Security', 'Tools', 'Training Techniques']
---
The rapid scaling of large language models (LLMs) has raised concerns about the transparency and fair use of the pretraining data used for training them. Detecting such content is challenging due to the scale of the data and limited exposure of each instance during training. We propose ReCaLL (Relative Conditional Log-Likelihood) a novel membership inference attack (MIA) to detect LLMs pretraining data by leveraging their conditional language modeling capabilities. ReCaLL examines the relative change in conditional log-likelihoods when prefixing target data points with non-member context. Our empirical findings show that conditioning member data on non-member prefixes induces a larger decrease in log-likelihood compared to non-member data. We conduct comprehensive experiments and show that ReCaLL achieves state-of-the-art performance on the WikiMIA dataset even with random and synthetic prefixes and can be further improved using an ensemble approach. Moreover we conduct an in-depth analysis of LLMs behavior with different membership contexts providing insights into how LLMs leverage membership information for effective inference at both the sequence and token level.
