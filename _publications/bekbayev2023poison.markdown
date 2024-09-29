---
layout: publication
title: The Poison Of Alignment
authors: Bekbayev Aibek, Chun Sungbae, Dulat Yerzat, Yamazaki James
conference: "Arxiv"
year: 2023
bibkey: bekbayev2023poison
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.13449"}
tags: ['Applications', 'RAG', 'Responsible AI']
---
From the perspective of content safety issues alignment has shown to limit large language models (LLMs) harmful content generation. This intentional method of reinforcing models to not respond to certain user inputs seem to be present in many modern open45;source instruction tuning datasets such as OpenAssistant or Guanaco. We introduce a novel insight to an instruction45;tuned models performance affected by the presence of alignment in supervised fine45;tuning dataset. To be specific we noticed that alignment acts as if it is poisoning the instruction dataset. Experimentally we demonstrate that aligned answers significantly worsen the performance of the resulting fine45;tuned models on various reasoning benchmarks such as Big Bench (BBH) Massive Multitask Language Understanding (MMLU) Human Eval and Discrete Reasoning Over Paragraphs (DROP) performing worse than the counterpart tuned without alignment by 445;3337;.
