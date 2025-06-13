---
layout: publication
title: 'RIDE: Enhancing Large Language Model Alignment Through Restyled In-context Learning Demonstration Exemplars'
authors: Yuncheng Hua, Lizhen Qu, Zhuang Li, Hao Xue, Flora D. Salim, Gholamreza Haffari
conference: "Arxiv"
year: 2025
bibkey: hua2025enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.11681"}
  - {name: "Code", url: "https://github.com/AnonymousCode-ComputerScience/RIDE"}
tags: ['Responsible AI', 'Tools', 'RAG', 'Training Techniques', 'Has Code', 'Few-Shot', 'Prompting', 'In-Context Learning']
---
Alignment tuning is crucial for ensuring large language models (LLMs) behave
ethically and helpfully. Current alignment approaches require high-quality
annotations and significant training resources. This paper proposes a low-cost,
tuning-free method using in-context learning (ICL) to enhance LLM alignment.
Through an analysis of high-quality ICL demos, we identified style as a key
factor influencing LLM alignment capabilities and explicitly restyled ICL
exemplars based on this stylistic framework. Additionally, we combined the
restyled demos to achieve a balance between the two conflicting aspects of LLM
alignment--factuality and safety. We packaged the restyled examples as prompts
to trigger few-shot learning, improving LLM alignment. Compared to the best
baseline approach, with an average score of 5.00 as the maximum, our method
achieves a maximum 0.10 increase on the Alpaca task (from 4.50 to 4.60), a 0.22
enhancement on the Just-eval benchmark (from 4.34 to 4.56), and a maximum
improvement of 0.32 (from 3.53 to 3.85) on the MT-Bench dataset. We release the
code and data at https://github.com/AnonymousCode-ComputerScience/RIDE.
