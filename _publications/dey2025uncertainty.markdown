---
layout: publication
title: 'Uncertainty-aware Fusion: An Ensemble Framework For Mitigating Hallucinations In Large Language Models'
authors: Prasenjit Dey, Srujana Merugu, Sivaramakrishnan Kaveri
conference: "Arxiv"
year: 2025
bibkey: dey2025uncertainty
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.05757"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'Merging', 'GPT', 'Applications']
---
Large Language Models (LLMs) are known to hallucinate and generate
non-factual outputs which can undermine user trust. Traditional methods to
directly mitigate hallucinations, such as representation editing and
contrastive decoding, often require additional training data and involve high
implementation complexity. While ensemble-based approaches harness multiple
LLMs to tap into the "wisdom of crowds", these methods overlook uncertainties
in individual model responses. Recent studies reveal that uncertainty
estimation can enable LLMs to self-assess the likelihood of generating
hallucinations. In this work, we focus on factoid question answering (QA) and
observe that LLMs accuracy and self-assessment capabilities vary widely with
different models excelling in different scenarios. Leveraging this insight, we
propose Uncertainty-Aware Fusion (UAF), an ensemble framework to reduces
hallucinations by strategically combining multiple LLM based on their accuracy
and self-assessment abilities. Empirical results on several public benchmark
datasets show that UAF outperforms state-of-the-art hallucination mitigation
methods by \\(8%\\) in factual accuracy, while either narrowing or surpassing the
performance gap with GPT-4.
