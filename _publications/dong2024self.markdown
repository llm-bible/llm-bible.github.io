---
layout: publication
title: Self45;play With Execution Feedback Improving Instruction45;following Capabilities Of Large Language Models
authors: Dong Guanting, Lu Keming, Li Chengpeng, Xia Tingyu, Yu Bowen, Zhou Chang, Zhou Jingren
conference: "Arxiv"
year: 2024
bibkey: dong2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.13542"}
  - {name: "Code", url: "https://github.com/QwenLM/AutoIF"}
tags: ['Agentic', 'Distillation', 'Efficiency And Optimization', 'Fine Tuning', 'Has Code', 'Reinforcement Learning', 'Training Techniques']
---
One core capability of large language models (LLMs) is to follow natural language instructions. However the issue of automatically constructing high45;quality training data to enhance the complex instruction45;following abilities of LLMs without manual annotation remains unresolved. In this paper we introduce AutoIF the first scalable and reliable method for automatically generating instruction45;following training data. AutoIF transforms the validation of instruction45;following data quality into code verification requiring LLMs to generate instructions the corresponding code to check the correctness of the instruction responses and unit test samples to verify the codes correctness. Then execution feedback45;based rejection sampling can generate data for Supervised Fine45;Tuning (SFT) and Reinforcement Learning from Human Feedback (RLHF) training. AutoIF achieves significant improvements across three training algorithms SFT Offline DPO and Online DPO when applied to the top open45;source LLMs Qwen2 and LLaMA3 in self45;alignment and strong45;to45;weak distillation settings. Our code is publicly available at https://github.com/QwenLM/AutoIF.
