---
layout: publication
title: Investigating Table-to-Text Generation Capabilities of LLMs in Real-World Information Seeking Scenarios
authors: Zhao Yilun, Zhang Haowei, Si Shengyun, Nan Linyong, Tang Xiangru, Cohan Arman
conference: "Arxiv"
year: 2023
bibkey: zhao2023investigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14987"}
  - {name: "Code", url: "https://github.com/yale-nlp/LLM-T2T"}
tags: ['ARXIV', 'Applications', 'GPT', 'Has Code']
---
Tabular data is prevalent across various industries necessitating significant time and effort for users to understand and manipulate for their information-seeking purposes. The advancements in large language models (LLMs) have shown enormous potential to improve user efficiency. However the adoption of LLMs in real-world applications for table information seeking remains underexplored. In this paper we investigate the table-to-text capabilities of different LLMs using four datasets within two real-world information seeking scenarios. These include the LogicNLG and our newly-constructed LoTNLG datasets for data insight generation along with the FeTaQA and our newly-constructed F2WTQ datasets for query-based generation. We structure our investigation around three research questions evaluating the performance of LLMs in table-to-text generation automated evaluation and feedback generation respectively. Experimental results indicate that the current high-performing LLM specifically GPT-4 can effectively serve as a table-to-text generator evaluator and feedback generator facilitating users information seeking purposes in real-world scenarios. However a significant performance gap still exists between other open-sourced LLMs (e.g. Tulu and LLaMA-2) and GPT-4 models. Our data and code are publicly available at https://github.com/yale-nlp/LLM-T2T.
