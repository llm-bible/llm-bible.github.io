---
layout: publication
title: Revisiting Large Language Models As Zero45;shot Relation Extractors
authors: Li Guozheng, Wang Peng, Ke Wenjun
conference: "Arxiv"
year: 2023
bibkey: li2023revisiting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.05028"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
Relation extraction (RE) consistently involves a certain degree of labeled or unlabeled data even if under zero45;shot setting. Recent studies have shown that large language models (LLMs) transfer well to new tasks out45;of45;the45;box simply given a natural language prompt which provides the possibility of extracting relations from text without any data and parameter tuning. This work focuses on the study of exploring LLMs such as ChatGPT as zero45;shot relation extractors. On the one hand we analyze the drawbacks of existing RE prompts and attempt to incorporate recent prompt techniques such as chain45;of45;thought (CoT) to improve zero45;shot RE. We propose the summarize45;and45;ask (textsc123;SumAsk125;) prompting a simple prompt recursively using LLMs to transform RE inputs to the effective question answering (QA) format. On the other hand we conduct comprehensive experiments on various benchmarks and settings to investigate the capabilities of LLMs on zero45;shot RE. Specifically we have the following findings (i) textsc123;SumAsk125; consistently and significantly improves LLMs performance on different model sizes benchmarks and settings; (ii) Zero45;shot prompting with ChatGPT achieves competitive or superior results compared with zero45;shot and fully supervised methods; (iii) LLMs deliver promising performance in extracting overlapping relations; (iv) The performance varies greatly regarding different relations. Different from small language models LLMs are effective in handling challenge none45;of45;the45;above (NoTA) relation.
