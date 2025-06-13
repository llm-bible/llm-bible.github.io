---
layout: publication
title: 'EVALALIGN: Supervised Fine-tuning Multimodal Llms With Human-aligned Data For Evaluating Text-to-image Models'
authors: Zhiyu Tan, Xiaomeng Yang, Luozheng Qin, Mengping Yang, Cheng Zhang, Hao Li
conference: "Arxiv"
year: 2024
bibkey: tan2024supervised
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.16562"}
tags: ['Multimodal Models', 'Training Techniques', 'Efficiency and Optimization', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning']
---
The recent advancements in text-to-image generative models have been
remarkable. Yet, the field suffers from a lack of evaluation metrics that
accurately reflect the performance of these models, particularly lacking
fine-grained metrics that can guide the optimization of the models. In this
paper, we propose EvalAlign, a metric characterized by its accuracy, stability,
and fine granularity. Our approach leverages the capabilities of Multimodal
Large Language Models (MLLMs) pre-trained on extensive data. We develop
evaluation protocols that focus on two key dimensions: image faithfulness and
text-image alignment. Each protocol comprises a set of detailed, fine-grained
instructions linked to specific scoring options, enabling precise manual
scoring of the generated images. We supervised fine-tune (SFT) the MLLM to
align with human evaluative judgments, resulting in a robust evaluation model.
Our evaluation across 24 text-to-image generation models demonstrate that
EvalAlign not only provides superior metric stability but also aligns more
closely with human preferences than existing metrics, confirming its
effectiveness and utility in model assessment.
