---
layout: publication
title: 'Enhancing SLM Via Chatgpt And Dataset Augmentation'
authors: Tom Pieper, Mohamad Ballout, Ulf Krumnack, Gunther Heidemann, Kai-uwe Kühnberger
conference: "Arxiv"
year: 2024
bibkey: pieper2024enhancing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.12599'}
tags: ['RAG', 'Efficiency and Optimization', 'Distillation', 'Training Techniques', 'Model Architecture', 'GPT', 'Fine-Tuning', 'Pretraining Methods']
---
This paper explores the enhancement of small language models through
strategic dataset augmentation via ChatGPT-3.5-Turbo, in the domain of Natural
Language Inference (NLI). By employing knowledge distillation-based techniques
and synthetic dataset augmentation, we aim to bridge the performance gap
between large language models (LLMs) and small language models (SLMs) without
the immense cost of human annotation. Our methods involve two forms of
rationale generation--information extraction and informed reasoning--to enrich
the ANLI dataset. We then fine-tune T5-Small on these augmented datasets,
evaluating its performance against an established benchmark. Our findings
reveal that the incorporation of synthetic rationales significantly improves
the model's ability to comprehend natural language, leading to 1.3% and 2.3%
higher classification accuracy, respectively, on the ANLI dataset,
demonstrating the potential of leveraging LLMs for dataset augmentation. This
approach not only enhances the performance of smaller models on complex tasks
but also introduces a cost-effective method for fine-tuning smaller language
models. By advancing our understanding of knowledge distillation and
fine-tuning strategies, this work contributes to the ongoing effort to create
more capable and efficient NLP systems.
