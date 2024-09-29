---
layout: publication
title: Evaluation Of Llms On Syntax-aware Code Fill-in-the-middle Tasks
authors: Gong Linyuan, Wang Sida, Elhoushi Mostafa, Cheung Alvin
conference: "Arxiv"
year: 2024
bibkey: gong2024evaluation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.04814"}
  - {name: "Code", url: "https://github.com/gonglinyuan/safim,"}
  - {name: "Code", url: "https://safimbenchmark.com"}
tags: ['Has Code', 'Pretraining Methods', 'Prompting', 'Tools', 'Training Techniques']
---
We introduce Syntax-Aware Fill-In-the-Middle (SAFIM) a new benchmark for evaluating Large Language Models (LLMs) on the code Fill-in-the-Middle (FIM) task. This benchmark focuses on syntax-aware completions of program structures such as code blocks and conditional expressions and includes 17720 examples from multiple programming languages sourced from recent code submissions after April 2022 to minimize data contamination. SAFIM provides a robust framework with various prompt designs and novel syntax-aware post-processing techniques facilitating accurate and fair comparisons across LLMs. Our comprehensive evaluation of 15 LLMs shows that FIM pretraining not only enhances FIM proficiency but also improves Left-to-Right (L2R) inference using LLMs. Our findings challenge conventional beliefs and suggest that pretraining methods and data quality have more impact than model size. SAFIM thus serves as a foundational platform for future research in effective pretraining strategies for code LLMs. The evaluation toolkit and dataset are available at https://github.com/gonglinyuan/safim, and the leaderboard is available at https://safimbenchmark.com.
