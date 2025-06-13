---
layout: publication
title: 'Layer Importance And Hallucination Analysis In Large Language Models Via Enhanced Activation Variance-sparsity'
authors: Zichen Song, Sitan Huang, Yuxin Wu, Zhongfeng Kang
conference: "Arxiv"
year: 2024
bibkey: song2024layer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.10069"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Tools', 'Language Modeling', 'Pruning', 'Interpretability and Explainability', 'Applications']
---
Evaluating the importance of different layers in large language models (LLMs)
is crucial for optimizing model performance and interpretability. This paper
first explores layer importance using the Activation Variance-Sparsity Score
(AVSS), which combines normalized activation variance and sparsity to quantify
each layer's contribution to overall model performance. By ranking layers based
on AVSS and pruning the least impactful 25%, our experiments on tasks such as
question answering, language modeling, and sentiment classification show that
over 90% of the original performance is retained, highlighting potential
redundancies in LLM architectures. Building on AVSS, we propose an enhanced
version tailored to assess hallucination propensity across layers (EAVSS). This
improved approach introduces Hallucination-Specific Activation Variance (HSAV)
and Hallucination-Specific Sparsity (HSS) metrics, allowing precise
identification of hallucination-prone layers. By incorporating contrastive
learning on these layers, we effectively mitigate hallucination generation,
contributing to more robust and efficient LLMs(The maximum performance
improvement is 12%). Our results on the NQ, SciQ, TriviaQA, TruthfulQA, and
WikiQA datasets demonstrate the efficacy of this method, offering a
comprehensive framework for both layer importance evaluation and hallucination
mitigation in LLMs.
