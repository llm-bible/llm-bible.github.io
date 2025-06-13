---
layout: publication
title: 'Bridging The Data Gap Between Training And Inference For Unsupervised Neural Machine Translation'
authors: Zhiwei He, Xing Wang, Rui Wang, Shuming Shi, Zhaopeng Tu
conference: "Arxiv"
year: 2022
bibkey: he2022bridging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2203.08394"}
tags: ['Ethics and Bias', 'Training Techniques', 'Applications']
---
Back-translation is a critical component of Unsupervised Neural Machine
Translation (UNMT), which generates pseudo parallel data from target
monolingual data. A UNMT model is trained on the pseudo parallel data with
translated source, and translates natural source sentences in inference. The
source discrepancy between training and inference hinders the translation
performance of UNMT models. By carefully designing experiments, we identify two
representative characteristics of the data gap in source: (1) style gap (i.e.,
translated vs. natural text style) that leads to poor generalization
capability; (2) content gap that induces the model to produce hallucination
content biased towards the target language. To narrow the data gap, we propose
an online self-training approach, which simultaneously uses the pseudo parallel
data \{natural source, translated target\} to mimic the inference scenario.
Experimental results on several widely-used language pairs show that our
approach outperforms two strong baselines (XLM and MASS) by remedying the style
and content gaps.
