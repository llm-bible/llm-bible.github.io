---
layout: publication
title: 'Babystories: Can Reinforcement Learning Teach Baby Language Models To Write Better Stories?'
authors: Xingmeng Zhao, Tongnian Wang, Sheri Osborn, Anthony Rios
conference: "Arxiv"
year: 2023
bibkey: zhao2023can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.16681"}
  - {name: "Code", url: "https://github.com/Zephyr1022/BabyStories-UTSA"}
tags: ['Agentic', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Has Code']
---
Language models have seen significant growth in the size of their corpus,
leading to notable performance improvements. Yet, there has been limited
progress in developing models that handle smaller, more human-like datasets. As
part of the BabyLM shared task, this study explores the impact of reinforcement
learning from human feedback (RLHF) on language models pretrained from scratch
with a limited training corpus. Comparing two GPT-2 variants, the larger model
performs better in storytelling tasks after RLHF fine-tuning. These findings
suggest that RLHF techniques may be more advantageous for larger models due to
their higher learning and adaptation capacity, though more experiments are
needed to confirm this finding. These insights highlight the potential benefits
of RLHF fine-tuning for language models within limited data, enhancing their
ability to maintain narrative focus and coherence while adhering better to
initial instructions in storytelling tasks. The code for this work is publicly
at https://github.com/Zephyr1022/BabyStories-UTSA.
