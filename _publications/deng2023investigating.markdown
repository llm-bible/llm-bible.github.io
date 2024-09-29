---
layout: publication
title: Investigating Data Contamination in Modern Benchmarks for Large Language Models
authors: Deng Chunyuan, Zhao Yilun, Tang Xiangru, Gerstein Mark, Cohan Arman
conference: "Arxiv"
year: 2023
bibkey: deng2023investigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09783"}
tags: ['Ethics And Bias', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Recent observations have underscored a disparity between the inflated benchmark scores and the actual performance of LLMs raising concerns about potential contamination of evaluation benchmarks. This issue is especially critical for closed-source models and certain open-source models where training data transparency is lacking. In this paper we study data contamination by proposing two methods tailored for both open-source and proprietary LLMs. We first introduce a retrieval-based system to explore potential overlaps between evaluation benchmarks and pretraining corpora. We further present a novel investigation protocol named estset lot Guessing () applicable to both open and proprietary models. This approach entails masking a wrong answer in a multiple-choice question and prompting the model to fill in the gap. Additionally it involves obscuring an unlikely word in an evaluation example and asking the model to produce it. We find that certain commercial LLMs could surprisingly guess the missing option in various test sets. Specifically in the TruthfulQA benchmark we find that LLMs exhibit notable performance improvement when provided with additional metadata in the benchmark. Further in the MMLU benchmark ChatGPT and GPT-4 demonstrated an exact match rate of 52 and 57 respectively in guessing the missing options in benchmark test data. We hope these results underscore the need for more robust evaluation methodologies and benchmarks in the field.
