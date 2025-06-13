---
layout: publication
title: 'Infinite-instruct: Synthesizing Scaling Code Instruction Data With Bidirectional Synthesis And Static Verification'
authors: Wenjing Xing, Wenke Lu, Yeheng Duan, Bing Zhao, Zhenghui Kang, Yaolong Wang, Kai Gao, Lei Qiao
conference: "Arxiv"
year: 2025
bibkey: xing2025infinite
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.23177'}
  - {name: "Code", url: 'https://github.com/xingwenjing417/Infinite-Instruct-dataset'}
tags: ['Has Code', 'RAG', 'Training Techniques', 'Applications', 'Tools', 'Fine-Tuning', 'Pretraining Methods']
---
Traditional code instruction data synthesis methods suffer from limited diversity and poor logic. We introduce Infinite-Instruct, an automated framework for synthesizing high-quality question-answer pairs, designed to enhance the code generation capabilities of large language models (LLMs). The framework focuses on improving the internal logic of synthesized problems and the quality of synthesized code. First, "Reverse Construction" transforms code snippets into diverse programming problems. Then, through "Backfeeding Construction," keywords in programming problems are structured into a knowledge graph to reconstruct them into programming problems with stronger internal logic. Finally, a cross-lingual static code analysis pipeline filters invalid samples to ensure data quality. Experiments show that on mainstream code generation benchmarks, our fine-tuned models achieve an average performance improvement of 21.70% on 7B-parameter models and 36.95% on 32B-parameter models. Using less than one-tenth of the instruction fine-tuning data, we achieved performance comparable to the Qwen-2.5-Coder-Instruct. Infinite-Instruct provides a scalable solution for LLM training in programming. We open-source the datasets used in the experiments, including both unfiltered versions and filtered versions via static analysis. The data are available at https://github.com/xingwenjing417/Infinite-Instruct-dataset
