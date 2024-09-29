---
layout: publication
title: Octopack: Instruction Tuning Code Large Language Models
authors: Muennighoff Niklas, Liu Qian, Zebaze Armel, Zheng Qinkai, Hui Binyuan, Zhuo Terry Yue, Singh Swayam, Tang Xiangru, Von Werra Leandro, Longpre Shayne
conference: "Arxiv"
year: 2023
bibkey: muennighoff2023instruction
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.07124"}
  - {name: "Code", url: "https://github.com/bigcode-project/octopack"}
tags: ['Has Code', 'Interpretability And Explainability', 'Pretraining Methods', 'RAG']
---
Finetuning large language models (LLMs) on instructions leads to vast performance improvements on natural language tasks. We apply instruction tuning using code leveraging the natural structure of Git commits which pair code changes with human instructions. We compile CommitPack 4 terabytes of Git commits across 350 programming languages. We benchmark CommitPack against other natural and synthetic code instructions (xP3x Self-Instruct OASST) on the 16B parameter StarCoder model and achieve state-of-the-art performance among models not trained on OpenAI outputs on the HumanEval Python benchmark (46.237; pass@1). We further introduce HumanEvalPack expanding the HumanEval benchmark to a total of 3 coding tasks (Code Repair Code Explanation Code Synthesis) across 6 languages (Python JavaScript Java Go C++ Rust). Our models OctoCoder and OctoGeeX achieve the best performance across HumanEvalPack among all permissive models demonstrating CommitPacks benefits in generalizing to a wider set of languages and natural coding tasks. Code models and data are freely available at https://github.com/bigcode-project/octopack."
