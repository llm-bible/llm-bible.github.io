---
layout: publication
title: 'Low-cost Generation And Evaluation Of Dictionary Example Sentences'
authors: Cai Bill, Ng Clarence Boon Liang, Tan Daniel, Hotama Shelvia
conference: "Arxiv"
year: 2024
bibkey: cai2024low
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.06224"}
tags: ['BERT', 'Masked Language Model', 'Pretraining Methods', 'Reinforcement Learning', 'Tools']
---
Dictionary example sentences play an important role in illustrating word definitions and usage but manually creating quality sentences is challenging. Prior works have demonstrated that language models can be trained to generate example sentences. However they relied on costly customized models and word sense datasets for generation and evaluation of their work. Rapid advancements in foundational models present the opportunity to create low-cost zero-shot methods for the generation and evaluation of dictionary example sentences. We introduce a new automatic evaluation metric called OxfordEval that measures the win-rate of generated sentences against existing Oxford Dictionary sentences. OxfordEval shows high alignment with human judgments enabling large-scale automated quality evaluation. We experiment with various LLMs and configurations to generate dictionary sentences across word classes. We complement this with a novel approach of using masked language models to identify and select sentences that best exemplify word meaning. The eventual model FM-MLM achieves over 85.137; win rate against Oxford baseline sentences according to OxfordEval compared to 39.837; win rate for prior model-generated sentences.
