---
layout: publication
title: Better Alignment With Instruction Back45;and45;forth Translation
authors: Nguyen Thao, Li Jeffrey, Oh Sewoong, Schmidt Ludwig, Weston Jason, Zettlemoyer Luke, Li Xian
conference: "Arxiv"
year: 2024
bibkey: nguyen2024better
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.04614"}
tags: ['Distillation', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Reinforcement Learning']
---
We propose a new method instruction back45;and45;forth translation to construct high45;quality synthetic data grounded in world knowledge for aligning large language models (LLMs). Given documents from a web corpus we generate and curate synthetic instructions using the backtranslation approach proposed by Li et al.(2023a) and rewrite the responses to improve their quality further based on the initial documents. Fine45;tuning with the resulting (backtranslated instruction rewritten response) pairs yields higher win rates on AlpacaEval than using other common instruction datasets such as Humpback ShareGPT Open Orca Alpaca45;GPT4 and Self45;instruct. We also demonstrate that rewriting the responses with an LLM outperforms direct distillation and the two generated text distributions exhibit significant distinction in embedding space. Further analysis shows that our backtranslated instructions are of higher quality than other sources of synthetic instructions while our responses are more diverse and complex than those obtained from distillation. Overall we find that instruction back45;and45;forth translation combines the best of both worlds 45;45; making use of the information diversity and quantity found on the web while ensuring the quality of the responses which is necessary for effective alignment.
