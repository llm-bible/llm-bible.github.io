---
layout: publication
title: Small Language Models Need Strong Verifiers To Self45;correct Reasoning
authors: Zhang Yunxiang, Khalifa Muhammad, Logeswaran Lajanugen, Kim Jaekyeom, Lee Moontae, Lee Honglak, Wang Lu
conference: "Arxiv"
year: 2024
bibkey: zhang2024small
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.17140"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Self45;correction has emerged as a promising solution to boost the reasoning performance of large language models (LLMs) where LLMs refine their solutions using self45;generated critiques that pinpoint the errors. This work explores whether small (<= 13B) language models (LMs) have the ability of self45;correction on reasoning tasks with minimal inputs from stronger LMs. We propose a novel pipeline that prompts smaller LMs to collect self45;correction data that supports the training of self45;refinement abilities. First we leverage correct solutions to guide the model in critiquing their incorrect responses. Second the generated critiques after filtering are used for supervised fine45;tuning of the self45;correcting reasoner through solution refinement. Our experimental results show improved self45;correction abilities of two models on five datasets spanning math and commonsense reasoning with notable performance gains when paired with a strong GPT45;445;based verifier though limitations are identified when using a weak self45;verifier for determining when to correct.
