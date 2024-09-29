---
layout: publication
title: Improving Multilingual Instruction Finetuning Via Linguistically Natural And Diverse Datasets
authors: Indurthi Sathish Reddy, Zhou Wenxuan, Chollampatt Shamil, Agrawal Ravi, Song Kaiqiang, Zhao Lingxiao, Zhu Chenguang
conference: "Arxiv"
year: 2024
bibkey: indurthi2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.01853"}
tags: ['Applications', 'Prompting', 'RAG']
---
Advancements in Large Language Models (LLMs) have significantly enhanced instruction45;following capabilities. However most Instruction Fine45;Tuning (IFT) datasets are predominantly in English limiting model performance in other languages. Traditional methods for creating multilingual IFT datasets such as translating existing English IFT datasets or converting existing NLP datasets into IFT datasets by templating struggle to capture linguistic nuances and ensure prompt (instruction) diversity. To address this issue we propose a novel method for collecting multilingual IFT datasets that preserves linguistic naturalness and ensures prompt diversity. This approach leverages English45;focused LLMs monolingual corpora and a scoring function to create high45;quality diversified IFT datasets in multiple languages. Experiments demonstrate that LLMs finetuned using these IFT datasets show notable improvements in both generative and discriminative tasks indicating enhanced language comprehension by LLMs in non45;English contexts. Specifically on the multilingual summarization task LLMs using our IFT dataset achieved 17.5737; and 15.2337; improvements over LLMs fine45;tuned with translation45;based and template45;based datasets respectively.
