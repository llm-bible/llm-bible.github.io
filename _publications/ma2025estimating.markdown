---
layout: publication
title: 'Estimating LLM Uncertainty With Evidence'
authors: Huan Ma, Jingdong Chen, Joey Tianyi Zhou, Guangyu Wang, Changqing Zhang
conference: "Arxiv"
year: 2025
bibkey: ma2025estimating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.00290"}
tags: ['Training Techniques', 'Tools', 'Reinforcement Learning']
---
Over the past few years, Large Language Models (LLMs) have developed rapidly and are widely applied in various domains. However, LLMs face the issue of hallucinations, generating responses that may be unreliable when the models lack relevant knowledge. To be aware of potential hallucinations, uncertainty estimation methods have been introduced, and most of them have confirmed that reliability lies in critical tokens. However, probability-based methods perform poorly in identifying token reliability, limiting their practical utility. In this paper, we reveal that the probability-based method fails to estimate token reliability due to the loss of evidence strength information which is accumulated in the training stage. Therefore, we present Logits-induced token uncertainty (LogTokU), a framework for estimating decoupled token uncertainty in LLMs, enabling real-time uncertainty estimation without requiring multiple sampling processes. We employ evidence modeling to implement LogTokU and use the estimated uncertainty to guide downstream tasks. The experimental results demonstrate that LogTokU has significant effectiveness and promise.
