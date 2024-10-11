---
layout: publication
title: 'Raw Text Is All You Need: Knowledge-intensive Multi-turn Instruction Tuning For Large Language Model'
authors: Hou Xia, Li Qifeng, Yang Jian, Li Tongliang, Chai Linzheng, Wu Xianjie, Ji Hangyuan, Li Zhoujun, Nie Jixuan, Dun Jingbo, Song Wenfeng
conference: "Arxiv"
year: 2024
bibkey: hou2024raw
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.03040"}
tags: ['Fine Tuning', 'Prompting', 'RAG', 'Tools', 'Uncategorized']
---
Instruction tuning as an effective technique aligns the outputs of large language models (LLMs) with human preference. But how to generate the seasonal multi-turn dialogues from raw documents for instruction tuning still requires further exploration. In this paper, we present a novel framework named R2S that leverages the CoD-Chain of Dialogue logic to guide large language models (LLMs) in generating knowledge-intensive multi-turn dialogues for instruction tuning. By integrating raw documents from both open-source datasets and domain-specific web-crawled documents into a benchmark K-BENCH, we cover diverse areas such as Wikipedia (English), Science (Chinese), and Artifacts (Chinese). Our approach first decides the logic flow of the current dialogue and then prompts LLMs to produce key phrases for sourcing relevant response content. This methodology enables the creation of the G I NSTRUCT instruction dataset, retaining raw document knowledge within dialoguestyle interactions. Utilizing this dataset, we fine-tune GLLM, a model designed to transform raw documents into structured multi-turn dialogues, thereby injecting comprehensive domain knowledge into the SFT model for enhanced instruction tuning. This work signifies a stride towards refining the adaptability and effectiveness of LLMs in processing and generating more accurate, contextually nuanced responses across various fields.
