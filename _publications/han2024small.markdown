---
layout: publication
title: Small Language Model Can Self45;correct
authors: Han Haixia, Liang Jiaqing, Shi Jie, He Qianyu, Xiao Yanghua
conference: "Arxiv"
year: 2024
bibkey: han2024small
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.07301"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning']
---
Generative Language Models (LMs) such as ChatGPT have exhibited remarkable performance across various downstream tasks. Nevertheless one of their most prominent drawbacks is generating inaccurate or false information with a confident tone. Previous studies have devised sophisticated pipelines and prompts to induce large LMs to exhibit the capability for self45;correction. However large LMs are explicitly prompted to verify and modify its answers separately rather than completing all steps spontaneously like humans. Moreover these complex prompts are extremely challenging for small LMs to follow. In this paper we introduce the underline123;I125;ntrinsic underline123;S125;elf45;underline123;C125;orrection (ISC) in generative language models aiming to correct the initial output of LMs in a self45;triggered manner even for those small LMs with 6 billion parameters. Specifically we devise a pipeline for constructing self45;correction data and propose Partial Answer Masking (PAM) aiming to endow the model with the capability for intrinsic self45;correction through fine45;tuning. We conduct experiments using LMs with parameters sizes ranging from 6 billion to 13 billion in two tasks including commonsense reasoning and factual knowledge reasoning. Our experiments demonstrate that the outputs generated using ISC outperform those generated without self45;correction. We believe that the output quality of even small LMs can be further improved by empowering them with the ability to intrinsic self45;correct.
