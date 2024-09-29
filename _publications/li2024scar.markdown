---
layout: publication
title: SCAR Efficient Instruction-tuning For Large Language Models Via Style Consistency-aware Response Ranking
authors: Li Zhuang, Hua Yuncheng, Vu Thuy-trang, Zhan Haolan, Qu Lizhen, Haffari Gholamreza
conference: "Arxiv"
year: 2024
bibkey: li2024scar
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.10882"}
  - {name: "Code", url: "https://github.com/zhuang-li/SCAR"}
tags: ['Applications', 'Fine Tuning', 'Has Code', 'Training Techniques']
---
Recent studies have shown that maintaining a consistent response style by human experts and enhancing data quality in training sets can significantly improve the performance of fine-tuned Large Language Models (LLMs) while reducing the number of training examples needed. However the precise definition of style and the relationship between style data quality and LLM performance remains unclear. This research decomposes response style into presentation and composition styles and finds that among training data of similar quality those with higher style consistency lead to better LLM performance. Inspired by this we introduce Style Consistency-Aware Response Ranking (SCAR) which automatically prioritizes instruction-response pairs in the training set based on their response stylistic consistency. By selecting the most style-consistent examples ranging from the top 2537; to 0.737; of the full dataset the fine-tuned LLMs can match or even surpass the performance of models trained on the entire dataset in coding and open-ended question-answering benchmarks. Code and data are available at https://github.com/zhuang-li/SCAR .
