---
layout: publication
title: 'Arginstruct: Specialized Instruction Fine-tuning For Computational Argumentation'
authors: Maja Stahl, Timon Ziegenbein, Joonsuk Park, Henning Wachsmuth
conference: "Arxiv"
year: 2025
bibkey: stahl2025specialized
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.22076"}
tags: ['Fine-Tuning', 'Training Techniques', 'Pretraining Methods']
---
Training large language models (LLMs) to follow instructions has significantly enhanced their ability to tackle unseen tasks. However, despite their strong generalization capabilities, instruction-following LLMs encounter difficulties when dealing with tasks that require domain knowledge. This work introduces a specialized instruction fine-tuning for the domain of computational argumentation (CA). The goal is to enable an LLM to effectively tackle any unseen CA tasks while preserving its generalization capabilities. Reviewing existing CA research, we crafted natural language instructions for 105 CA tasks to this end. On this basis, we developed a CA-specific benchmark for LLMs that allows for a comprehensive evaluation of LLMs' capabilities in solving various CA tasks. We synthesized 52k CA-related instructions, adapting the self-instruct process to train a CA-specialized instruction-following LLM. Our experiments suggest that CA-specialized instruction fine-tuning significantly enhances the LLM on both seen and unseen CA tasks. At the same time, performance on the general NLP tasks of the SuperNI benchmark remains stable.
