---
layout: publication
title: Advancing Process Verification For Large Language Models Via Tree45;based Preference Learning
authors: He Mingqian, Shen Yongliang, Zhang Wenqi, Tan Zeqi, Lu Weiming
conference: "Arxiv"
year: 2024
bibkey: he2024advancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.00390"}
tags: ['Reinforcement Learning', 'Training Techniques']
---
Large Language Models (LLMs) have demonstrated remarkable potential in handling complex reasoning tasks by generating step45;by45;step rationales.Some methods have proven effective in boosting accuracy by introducing extra verifiers to assess these paths. However existing verifiers typically trained on binary45;labeled reasoning paths fail to fully utilize the relative merits of intermediate steps thereby limiting the effectiveness of the feedback provided. To overcome this limitation we propose Tree45;based Preference Learning Verifier (Tree45;PLV) a novel approach that constructs reasoning trees via a best45;first search algorithm and collects step45;level paired data for preference training. Compared to traditional binary classification step45;level preferences more finely capture the nuances between reasoning steps allowing for a more precise evaluation of the complete reasoning path. We empirically evaluate Tree45;PLV across a range of arithmetic and commonsense reasoning tasks where it significantly outperforms existing benchmarks. For instance Tree45;PLV achieved substantial performance gains over the Mistral45;7B self45;consistency baseline on GSM8K (67.5537; to 82.7937;) MATH (17.0037; to 26.8037;) CSQA (68.1437; to 72.9737;) and StrategyQA (82.8637; to 83.2537;).Additionally our study explores the appropriate granularity for applying preference learning revealing that step45;level guidance provides feedback that better aligns with the evaluation of the reasoning process.
