---
layout: publication
title: 'Bbox-adapter: Lightweight Adapting For Black-box Large Language Models'
authors: Haotian Sun, Yuchen Zhuang, Wei Wei, Chao Zhang, Bo Dai
conference: "Arxiv"
year: 2024
bibkey: sun2024bbox
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.08219"}
tags: ['Fine-Tuning', 'Tools', 'GPT', 'Efficiency and Optimization', 'Ethics and Bias', 'Model Architecture', 'Interpretability', 'Training Techniques', 'Pretraining Methods']
---
Adapting state-of-the-art Large Language Models (LLMs) like GPT-4 and Gemini
for specific tasks is challenging. Due to the opacity in their parameters,
embeddings, and even output probabilities, existing fine-tuning adaptation
methods are inapplicable. Consequently, adapting these black-box LLMs is only
possible through their API services, raising concerns about transparency,
privacy, and cost. To address these challenges, we introduce BBox-Adapter, a
novel lightweight adapter for black-box LLMs. BBox-Adapter distinguishes target
and source domain data by treating target data as positive and source data as
negative. It employs a ranking-based Noise Contrastive Estimation (NCE) loss to
promote the likelihood of target domain data while penalizing that of the
source domain. Furthermore, it features an online adaptation mechanism, which
incorporates real-time positive data sampling from ground-truth, human, or AI
feedback, coupled with negative data from previous adaptations. Extensive
experiments demonstrate BBox-Adapter's effectiveness and cost efficiency. It
improves model performance by up to 6.77% across diverse tasks and domains,
while reducing training and inference costs by 31.30x and 1.84x, respectively.
