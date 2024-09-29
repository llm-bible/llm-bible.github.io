---
layout: publication
title: USCD Improving Code Generation Of Llms By Uncertainty45;aware Selective Contrastive Decoding
authors: Wang Shuai, Ding Liang, Shen Li, Luo Yong, He Zheng, Yu Wei, Tao Dacheng
conference: "Arxiv"
year: 2024
bibkey: wang2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.05923"}
tags: ['Applications', 'Prompting', 'RAG', 'Reinforcement Learning']
---
Large language models (LLMs) have shown remarkable capabilities in code generation. However the effects of hallucinations (e.g. output noise) make it particularly challenging for LLMs to generate high45;quality code in one pass. In this work we propose a simple and effective textbf123;u125;ncertainty45;aware textbf123;s125;elective textbf123;c125;ontrastive textbf123;d125;ecoding (USCD) mechanism to improve the quality of one45;pass code generation in LLMs and reduce the impact of output noise. To be specific we first elaborately designed a negative prompt (namely lame prompt) to output noise by removing input45;output examples from the standard few45;shot prompt. Our preliminary study shows that the Jensen45;Shannon divergence (JS divergence) between token distribution uncertainty and the output noise is relatively low (approximately 0.25) indicating their high relevance. Then we selectively eliminate output noise induced by lame prompts based on the uncertainty of the prediction distribution from the standard prompt. Notably our proposed plug45;and45;play mechanism is an inference45;only method enjoying appealing flexibility. Extensive experiments on widely used benchmarks e.g. HumanEval MBPP and MultiPL45;E upon several LLMs (i.e. Inocder45;6b CodeLlama45;7b WizardCoder45;15b StarCoder and Llama245;7b) demonstrate that our proposed USCD significantly improves one45;pass code generation with an average textit123;pass35;64;1125; scores increase of 16.5937;. We will release code and data on GitHub.
