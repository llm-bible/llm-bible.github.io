---
layout: publication
title: 'KSOD: Knowledge Supplement For Llms On Demand'
authors: Haoran Li, Junfeng Hu
conference: "Arxiv"
year: 2025
bibkey: li2025knowledge
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.07550"}
tags: ['Pretraining Methods', 'Training Techniques', 'Fine-Tuning', 'Tools']
---
Large Language Models (LLMs) have demonstrated remarkable capabilities in
various tasks, yet still produce errors in domain-specific tasks. To further
improve their performance, we propose KSOD (Knowledge Supplement for LLMs On
Demand), a novel framework that empowers LLMs to improve their capabilities
with knowledge-based supervised fine-tuning (SFT). KSOD analyzes the causes of
errors from the perspective of knowledge deficiency by identifying potential
missing knowledge in LLM that may lead to the errors. Subsequently, KSOD tunes
a knowledge module on knowledge dataset and verifies whether the LLM lacks the
identified knowledge based on it. If the knowledge is verified, KSOD
supplements the LLM with the identified knowledge using the knowledge module.
Tuning LLMs on specific knowledge instead of specific task decouples task and
knowledge and our experiments on two domain-specific benchmarks and four
general benchmarks empirically demonstrate that KSOD enhances the performance
of LLMs on tasks requiring the supplemented knowledge while preserving their
performance on other tasks. Our findings shed light on the potential of
improving the capabilities of LLMs with knowledge-based SFT.
