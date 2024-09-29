---
layout: publication
title: 'Quantifying And Mitigating Unimodal Biases In Multimodal Large Language Models: A Causal Perspective'
authors: Chen Meiqi, Cao Yixin, Zhang Yan, Lu Chaochao
conference: "Arxiv"
year: 2024
bibkey: chen2024quantifying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.18346"}
tags: ['Applications', 'Ethics And Bias', 'Fine Tuning', 'Multimodal Models', 'Pretraining Methods', 'Tools', 'Training Techniques']
---
Recent advancements in Large Language Models (LLMs) have facilitated the development of Multimodal LLMs (MLLMs). Despite their impressive capabilities MLLMs often suffer from an over-reliance on unimodal biases (e.g. language bias and vision bias) leading to incorrect answers in complex multimodal tasks. To investigate this issue we propose a causal framework to interpret the biases in Visual Question Answering (VQA) problems. Within our framework we devise a causal graph to elucidate the predictions of MLLMs on VQA problems and assess the causal effect of biases through an in-depth causal analysis. Motivated by the causal graph we introduce a novel MORE dataset consisting of 12000 VQA instances. This dataset is designed to challenge MLLMs abilities necessitating multi-hop reasoning and the surmounting of unimodal biases. Furthermore we propose two strategies to mitigate unimodal biases and enhance MLLMs reasoning capabilities including a Decompose-Verify-Answer (DeVA) framework for limited-access MLLMs and the refinement of open-source MLLMs through fine-tuning. Extensive quantitative and qualitative experiments offer valuable insights for future research. Our project page is at https://opencausalab.github.io/MORE."
