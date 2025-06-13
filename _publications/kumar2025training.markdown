---
layout: publication
title: 'Training With Pseudo-code For Instruction Following'
authors: Prince Kumar, Rudra Murthy, Riyaz Bhat, Danish Contractor
conference: "Arxiv"
year: 2025
bibkey: kumar2025training
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.18011'}
tags: ['Few-Shot', 'RAG', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Pretraining Methods']
---
Despite the rapid progress in the capabilities of Large Language Models (LLMs), they continue to have difficulty following relatively simple, unambiguous instructions, especially when compositions are involved. In this paper, we take inspiration from recent work that suggests that models may follow instructions better when they are expressed in pseudo-code. However, writing pseudo-code programs can be tedious and using few-shot demonstrations to craft code representations for use in inference can be unnatural for non-expert users of LLMs. To overcome these limitations, we propose fine-tuning LLMs with instruction-tuning data that additionally includes instructions re-expressed in pseudo-code along with the final response. We evaluate models trained using our method on \\(11\\) publicly available benchmarks comprising of tasks related to instruction-following, mathematics, and common-sense reasoning. We conduct rigorous experiments with \\(5\\) different models and find that not only do models follow instructions better when trained with pseudo-code, they also retain their capabilities on the other tasks related to mathematical and common sense reasoning. Specifically, we observe a relative gain of \\(3\\)--\\(19\\)% on instruction-following benchmark, and an average gain of upto 14% across all tasks.
