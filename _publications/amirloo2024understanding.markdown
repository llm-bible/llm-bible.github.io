---
layout: publication
title: 'Understanding Alignment In Multimodal Llms: A Comprehensive Study'
authors: Elmira Amirloo, Jean-philippe Fauconnier, Christoph Roesmann, Christian Kerl, Rinu Boney, Yusu Qian, Zirui Wang, Afshin Dehghan, Yinfei Yang, Zhe Gan, Peter Grasch
conference: "Arxiv"
year: 2024
bibkey: amirloo2024understanding
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.02477'}
tags: ['RAG', 'Efficiency and Optimization', 'Multimodal Models', 'Survey Paper', 'Reinforcement Learning', 'Ethics and Bias']
---
Preference alignment has become a crucial component in enhancing the
performance of Large Language Models (LLMs), yet its impact in Multimodal Large
Language Models (MLLMs) remains comparatively underexplored. Similar to
language models, MLLMs for image understanding tasks encounter challenges like
hallucination. In MLLMs, hallucination can occur not only by stating incorrect
facts but also by producing responses that are inconsistent with the image
content. A primary objective of alignment for MLLMs is to encourage these
models to align responses more closely with image information. Recently,
multiple works have introduced preference datasets for MLLMs and examined
different alignment methods, including Direct Preference Optimization (DPO) and
Proximal Policy Optimization (PPO). However, due to variations in datasets,
base model types, and alignment methods, it remains unclear which specific
elements contribute most significantly to the reported improvements in these
works. In this paper, we independently analyze each aspect of preference
alignment in MLLMs. We start by categorizing the alignment algorithms into two
groups, offline (such as DPO), and online (such as online-DPO), and show that
combining offline and online methods can improve the performance of the model
in certain scenarios. We review a variety of published multimodal preference
datasets and discuss how the details of their construction impact model
performance. Based on these insights, we introduce a novel way of creating
multimodal preference data called Bias-Driven Hallucination Sampling (BDHS)
that needs neither additional annotation nor external models, and show that it
can achieve competitive performance to previously published alignment work for
multimodal models across a range of benchmarks.
