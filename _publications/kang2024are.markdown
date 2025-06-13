---
layout: publication
title: 'Are The Values Of Llms Structurally Aligned With Humans? A Causal Perspective'
authors: Yipeng Kang, Junqi Wang, Yexin Li, Mengmeng Wang, Wenming Tu, Quansen Wang, Hengli Li, Tingjun Wu, Xue Feng, Fangwei Zhong, Zilong Zheng
conference: "Arxiv"
year: 2024
bibkey: kang2024are
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.00581"}
tags: ['Agentic', 'Applications', 'Interpretability and Explainability', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Prompting']
---
As large language models (LLMs) become increasingly integrated into critical
applications, aligning their behavior with human values presents significant
challenges. Current methods, such as Reinforcement Learning from Human Feedback
(RLHF), typically focus on a limited set of coarse-grained values and are
resource-intensive. Moreover, the correlations between these values remain
implicit, leading to unclear explanations for value-steering outcomes. Our work
argues that a latent causal value graph underlies the value dimensions of LLMs
and that, despite alignment training, this structure remains significantly
different from human value systems. We leverage these causal value graphs to
guide two lightweight value-steering methods: role-based prompting and sparse
autoencoder (SAE) steering, effectively mitigating unexpected side effects.
Furthermore, SAE provides a more fine-grained approach to value steering.
Experiments on Gemma-2B-IT and Llama3-8B-IT demonstrate the effectiveness and
controllability of our methods.
