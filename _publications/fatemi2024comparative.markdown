---
layout: publication
title: 'A Comparative Analysis Of Instruction Fine-tuning Llms For Financial Text Classification'
authors: Sorouralsadat Fatemi, Yuheng Hu, Maryam Mousavi
conference: "Arxiv"
year: 2024
bibkey: fatemi2024comparative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.02476"}
tags: ['Pretraining Methods', 'Training Techniques', 'Fine-Tuning', 'Merging']
---
Large Language Models (LLMs) have demonstrated impressive capabilities across
diverse Natural Language Processing (NLP) tasks, including language
understanding, reasoning, and generation. However, general-domain LLMs often
struggle with financial tasks due to the technical and specialized nature of
financial texts. This study investigates the efficacy of instruction
fine-tuning smaller-scale LLMs, including Mistral-7B, Llama3-8B, and Phi3-mini,
to enhance their performance in financial text classification tasks. We
fine-tuned both instruction-tuned and base models across four financial
classification tasks, achieving significant improvements in task-specific
performance. Furthermore, we evaluated the zero-shot capabilities of these
fine-tuned models on three unseen complex financial tasks, including argument
classification, deal completeness classification, and causal classification.
Our results indicate while base model fine-tuning led to greater degradation,
instruction-tuned models maintained more robust performance. To address this
degradation, we employed model merging techniques, integrating single-task
domain-specific fine-tuned models with the base model. Using this merging
method resulted in significant enhancements in zero-shot performance, even
exceeding the original model's accuracy on certain datasets. Our findings
underscore the effectiveness of instruction fine-tuning and model merging for
adapting LLMs to specialized financial text classification tasks.
