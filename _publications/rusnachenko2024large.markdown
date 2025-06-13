---
layout: publication
title: 'Large Language Models In Targeted Sentiment Analysis'
authors: Nicolay Rusnachenko, Anton Golubev, Natalia Loukachevitch
conference: "Arxiv"
year: 2024
bibkey: rusnachenko2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.12342"}
  - {name: "Code", url: "https://github.com/nicolay-r/Reasoning-for-Sentiment-Analysis-Framework"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'Pretraining Methods', 'BERT', 'Transformer', 'Fine-Tuning', 'Has Code']
---
In this paper we investigate the use of decoder-based generative transformers
for extracting sentiment towards the named entities in Russian news articles.
We study sentiment analysis capabilities of instruction-tuned large language
models (LLMs). We consider the dataset of RuSentNE-2023 in our study. The first
group of experiments was aimed at the evaluation of zero-shot capabilities of
LLMs with closed and open transparencies. The second covers the fine-tuning of
Flan-T5 using the "chain-of-thought" (CoT) three-hop reasoning framework
(THoR). We found that the results of the zero-shot approaches are similar to
the results achieved by baseline fine-tuned encoder-based transformers
(BERT-base). Reasoning capabilities of the fine-tuned Flan-T5 models with THoR
achieve at least 5% increment with the base-size model compared to the results
of the zero-shot experiment. The best results of sentiment analysis on
RuSentNE-2023 were achieved by fine-tuned Flan-T5-xl, which surpassed the
results of previous state-of-the-art transformer-based classifiers. Our CoT
application framework is publicly available:
https://github.com/nicolay-r/Reasoning-for-Sentiment-Analysis-Framework
