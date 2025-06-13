---
layout: publication
title: 'Maintaining Informative Coherence: Migrating Hallucinations In Large Language Models Via Absorbing Markov Chains'
authors: Jiemin Wu, Songning Lai, Ruiqiang Xiao, Tianlang Xue, Jiayu Yang, Yutao Yue
conference: "Arxiv"
year: 2024
bibkey: wu2024maintaining
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.20340'}
tags: ['Language Modeling', 'RAG', 'Tools', 'Applications', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Ethics and Bias', 'Pretraining Methods']
---
Large Language Models (LLMs) are powerful tools for text generation,
translation, and summarization, but they often suffer from
hallucinations-instances where they fail to maintain the fidelity and coherence
of contextual information during decoding, sometimes overlooking critical
details due to their sampling strategies and inherent biases from training data
and fine-tuning discrepancies. These hallucinations can propagate through the
web, affecting the trustworthiness of information disseminated online. To
address this issue, we propose a novel decoding strategy that leverages
absorbing Markov chains to quantify the significance of contextual information
and measure the extent of information loss during generation. By considering
all possible paths from the first to the last token, our approach enhances the
reliability of model outputs without requiring additional training or external
data. Evaluations on datasets including TruthfulQA, FACTOR, and HaluEval
highlight the superior performance of our method in mitigating hallucinations,
underscoring the necessity of ensuring accurate information flow in web-based
applications.
