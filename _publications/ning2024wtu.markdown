---
layout: publication
title: 'WTU-EVAL: A Whether-or-not Tool Usage Evaluation Benchmark For Large Language Models'
authors: Ning Kangyun, Su Yisong, Lv Xueqiang, Zhang Yuanzhe, Liu Jian, Liu Kang, Xu Jinan
conference: "Arxiv"
year: 2024
bibkey: ning2024wtu
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.12823"}
tags: ['Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Although Large Language Models (LLMs) excel in NLP tasks, they still need external tools to extend their ability. Current research on tool learning with LLMs often assumes mandatory tool use, which does not always align with real-world situations, where the necessity for tools is uncertain, and incorrect or unnecessary use of tools can damage the general abilities of LLMs. Therefore, we propose to explore whether LLMs can discern their ability boundaries and use tools flexibly. We then introduce the Whether-or-not tool usage Evaluation benchmark (WTU-Eval) to assess LLMs with eleven datasets, where six of them are tool-usage datasets, and five are general datasets. LLMs are prompted to use tools according to their needs. The results of eight LLMs on WTU-Eval reveal that LLMs frequently struggle to determine tool use in general datasets, and LLMs' performance in tool-usage datasets improves when their ability is similar to ChatGPT. In both datasets, incorrect tool usage significantly impairs LLMs' performance. To mitigate this, we also develop the finetuning dataset to enhance tool decision-making. Fine-tuning Llama2-7B results in a 14\&#37; average performance improvement and a 16.8\&#37; decrease in incorrect tool usage. We will release the WTU-Eval benchmark.
