---
layout: publication
title: 'Probing Visual Language Priors In Vlms'
authors: Tiange Luo, Ang Cao, Gunhee Lee, Justin Johnson, Honglak Lee
conference: "Arxiv"
year: 2024
bibkey: luo2024probing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.00569"}
tags: ['Tools', 'GPT', 'Model Architecture', 'Training Techniques', 'Multimodal Models']
---
Despite recent advances in Vision-Language Models (VLMs), they may over-rely
on visual language priors existing in their training data rather than true
visual reasoning. To investigate this, we introduce ViLP, a benchmark featuring
deliberately out-of-distribution images synthesized via image generation models
and out-of-distribution Q&A pairs. Each question in ViLP is coupled with three
potential answers and three corresponding images: one that can be resolved by
text priors alone and two that demand visual reasoning. Although, humans
achieve near-perfect accuracy, modern VLMs falter; for instance, GPT-4 achieves
only 66.17% on ViLP. To alleviate this, we propose a self-improving framework
in which models generate new VQA data, then apply pixel-level and semantic
corruptions to form "good-bad" image pairs for self-training. Our training
objectives compel VLMs to focus more on the actual visual inputs, and we
demonstrate their effectiveness in boosting the performance of open-source
VLMs, including LLaVA-v1.5 and Cambrian.
