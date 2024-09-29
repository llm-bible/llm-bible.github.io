---
layout: publication
title: 'Advancing Process Verification For Large Language Models Via Tree-based Preference Learning'
authors: He Mingqian, Shen Yongliang, Zhang Wenqi, Tan Zeqi, Lu Weiming
conference: "Arxiv"
year: 2024
bibkey: he2024advancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.00390"}
tags: ['Reinforcement Learning', 'Training Techniques']
---
Large Language Models (LLMs) have demonstrated remarkable potential in handling complex reasoning tasks by generating step-by-step rationales.Some methods have proven effective in boosting accuracy by introducing extra verifiers to assess these paths. However existing verifiers typically trained on binary-labeled reasoning paths fail to fully utilize the relative merits of intermediate steps thereby limiting the effectiveness of the feedback provided. To overcome this limitation we propose Tree-based Preference Learning Verifier (Tree-PLV) a novel approach that constructs reasoning trees via a best-first search algorithm and collects step-level paired data for preference training. Compared to traditional binary classification step-level preferences more finely capture the nuances between reasoning steps allowing for a more precise evaluation of the complete reasoning path. We empirically evaluate Tree-PLV across a range of arithmetic and commonsense reasoning tasks where it significantly outperforms existing benchmarks. For instance Tree-PLV achieved substantial performance gains over the Mistral-7B self-consistency baseline on GSM8K (67.5537; to 82.7937;) MATH (17.0037; to 26.8037;) CSQA (68.1437; to 72.9737;) and StrategyQA (82.8637; to 83.2537;).Additionally our study explores the appropriate granularity for applying preference learning revealing that step-level guidance provides feedback that better aligns with the evaluation of the reasoning process.
