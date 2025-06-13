---
layout: publication
title: 'Deconfounded Causality-aware Parameter-efficient Fine-tuning For Problem-solving Improvement Of Llms'
authors: Ruoyu Wang, Xiaoxuan Li, Lina Yao
conference: "Arxiv"
year: 2024
bibkey: wang2024deconfounded
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.02686"}
tags: ['Fine-Tuning', 'Tools', 'Efficiency and Optimization', 'Applications', 'Interpretability and Explainability', 'RAG', 'Model Architecture', 'Language Modeling', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
Large Language Models (LLMs) have demonstrated remarkable efficiency in
tackling various tasks based on human instructions, but studies reveal that
they often struggle with tasks requiring reasoning, such as math or physics.
This limitation raises questions about whether LLMs truly comprehend embedded
knowledge or merely learn to replicate the token distribution without a true
understanding of the content. In this paper, we delve into this problem and aim
to enhance the reasoning capabilities of LLMs. First, we investigate if the
model has genuine reasoning capabilities by visualizing the text generation
process at the attention and representation level. Then, we formulate the
reasoning process of LLMs into a causal framework, which provides a formal
explanation of the problems observed in the visualization. Finally, building
upon this causal framework, we propose Deconfounded Causal Adaptation (DCA), a
novel parameter-efficient fine-tuning (PEFT) method to enhance the model's
reasoning capabilities by encouraging the model to extract the general
problem-solving skills and apply these skills to different questions.
Experiments show that our method outperforms the baseline consistently across
multiple benchmarks, and with only 1.2M tunable parameters, we achieve better
or comparable results to other fine-tuning methods. This demonstrates the
effectiveness and efficiency of our method in improving the overall accuracy
and reliability of LLMs.
