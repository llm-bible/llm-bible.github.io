---
layout: publication
title: 'Cfinbench: A Comprehensive Chinese Financial Benchmark For Large Language Models'
authors: Nie Ying, Yan Binwei, Guo Tianyu, Liu Hao, Wang Haoyu, He Wei, Zheng Binfan, Wang Weihao, Li Qiang, Sun Weijian, Wang Yunhe, Tao Dacheng
conference: "Arxiv"
year: 2024
bibkey: nie2024comprehensive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.02301"}
  - {name: "Code", url: "https://cfinbench.github.io/"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'RAG', 'Uncategorized']
---
Large language models (LLMs) have achieved remarkable performance on various NLP tasks, yet their potential in more challenging and domain-specific task, such as finance, has not been fully explored. In this paper, we present CFinBench: a meticulously crafted, the most comprehensive evaluation benchmark to date, for assessing the financial knowledge of LLMs under Chinese context. In practice, to better align with the career trajectory of Chinese financial practitioners, we build a systematic evaluation from 4 first-level categories: (1) Financial Subject: whether LLMs can memorize the necessary basic knowledge of financial subjects, such as economics, statistics and auditing. (2) Financial Qualification: whether LLMs can obtain the needed financial qualified certifications, such as certified public accountant, securities qualification and banking qualification. (3) Financial Practice: whether LLMs can fulfill the practical financial jobs, such as tax consultant, junior accountant and securities analyst. (4) Financial Law: whether LLMs can meet the requirement of financial laws and regulations, such as tax law, insurance law and economic law. CFinBench comprises 99,100 questions spanning 43 second-level categories with 3 question types: single-choice, multiple-choice and judgment. We conduct extensive experiments of 50 representative LLMs with various model size on CFinBench. The results show that GPT4 and some Chinese-oriented models lead the benchmark, with the highest average accuracy being 60.16&#37;, highlighting the challenge presented by CFinBench. The dataset and evaluation code are available at https://cfinbench.github.io/.
