---
layout: publication
title: "Improving Scheduled Sampling With Elastic Weight Consolidation For Neural Machine Translation"
authors: Korakakis Michalis, Vlachos Andreas
conference: "Arxiv"
year: 2021
bibkey: korakakis2021improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2109.06308"}
tags: ['Applications', 'Ethics And Bias', 'GPT', 'Language Modeling', 'Pretraining Methods', 'Training Techniques']
---
Despite strong performance in many sequence-to-sequence tasks autoregressive models trained with maximum likelihood estimation suffer from exposure bias i.e. the discrepancy between the ground-truth prefixes used during training and the model-generated prefixes used at inference time. Scheduled sampling is a simple and empirically successful approach which addresses this issue by incorporating model-generated prefixes into training. However it has been argued that it is an inconsistent training objective leading to models ignoring the prefixes altogether. In this paper we conduct systematic experiments and find that scheduled sampling while it ameliorates exposure bias by increasing model reliance on the input sequence worsens performance when the prefix at inference time is correct a form of catastrophic forgetting. We propose to use Elastic Weight Consolidation to better balance mitigating exposure bias with retaining performance. Experiments on four IWSLT14 and WMT14 translation datasets demonstrate that our approach alleviates catastrophic forgetting and significantly outperforms maximum likelihood estimation and scheduled sampling baselines.
