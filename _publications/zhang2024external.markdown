---
layout: publication
title: 'RECOST: External Knowledge Guided Data-efficient Instruction Tuning'
authors: Zhang Qi, Zhang Yiming, Wang Haobo, Zhao Junbo
conference: "Arxiv"
year: 2024
bibkey: zhang2024external
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.17355"}
tags: ['Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Tools', 'Training Techniques']
---
In the current landscape of large language models (LLMs) the process of instruction tuning serves as an essential step. Considering the high computing power overhead data-efficient instruction tuning was proposed to reduce the training data size in this process aiming at selecting high-quality instructional data. Nevertheless we argue that most current data-efficient instruction-tuning methods are highly dependent on the quality of the original instruction-tuning dataset. When it comes to datasets synthesized by LLMs a common scenario in this field dirty samples will even be selected with a higher probability than other samples. To address these challenges we utilized external knowledge (relevant examples or paragraphs) to evaluate those samples synthesized by LLMs with an in-context-based relative predictive entropy. Based on the new metric we proposed a framework dubbed as (textbfRECOST) which integrates external-knowledge-base re-ranking and diversity-consistent sampling into a single pipeline. Through extensive experiments on several synthetic datasets (Alpaca and Alpaca-gpt4) we demonstrate the effectiveness of our method and achieve even better results with only (textbf)137; of the full dataset.
