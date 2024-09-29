---
layout: publication
title: Structured Chain-of-thought Prompting For Code Generation
authors: Li Jia, Li Ge, Li Yongmin, Jin Zhi
conference: "Arxiv"
year: 2023
bibkey: li2023structured
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.06599"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Prompting']
---
Large Language Models (LLMs) (e.g. ChatGPT) have shown impressive performance in code generation. LLMs take prompts as inputs and Chain-of-Thought (CoT) prompting is the state-of-the-art prompting technique. CoT prompting asks LLMs first to generate CoTs (i.e. intermediate natural language reasoning steps) and then output the code. However CoT prompting is designed for natural language generation and has low accuracy in code generation. In this paper we propose Structured CoTs (SCoTs) and present a novel prompting technique for code generation named SCoT prompting. Our motivation is source code contains rich structural information and any code can be composed of three program structures (i.e. sequence branch and loop structures). Intuitively structured intermediate reasoning steps make for structured source code. Thus we ask LLMs to use program structures to build CoTs obtaining SCoTs. Then LLMs generate the final code based on SCoTs. Compared to CoT prompting SCoT prompting explicitly constrains LLMs to think about how to solve requirements from the view of source code and further the performance of LLMs in code generation. We apply SCoT prompting to two LLMs (i.e. ChatGPT and Codex) and evaluate it on three benchmarks (i.e. HumanEval MBPP and MBCPP). (1) SCoT prompting outperforms the state-of-the-art baseline - CoT prompting by up to 13.7937; in Pass35;64;1. (2) Human evaluation shows human developers prefer programs from SCoT prompting. (3) SCoT prompting is robust to examples and achieves substantial improvements.
