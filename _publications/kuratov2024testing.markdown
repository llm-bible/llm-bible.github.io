---
layout: publication
title: Babilong Testing The Limits Of Llms With Long Context Reasoning45;in45;a45;haystack
authors: Kuratov Yuri, Bulatov Aydar, Anokhin Petr, Rodkin Ivan, Sorokin Dmitry, Sorokin Artyom, Burtsev Mikhail
conference: "Arxiv"
year: 2024
bibkey: kuratov2024testing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.10149"}
tags: ['Applications', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Transformer']
---
In recent years the input context sizes of large language models (LLMs) have increased dramatically. However existing evaluation methods have not kept pace failing to comprehensively assess the efficiency of models in handling long contexts. To bridge this gap we introduce the BABILong benchmark designed to test language models ability to reason across facts distributed in extremely long documents. BABILong includes a diverse set of 20 reasoning tasks including fact chaining simple induction deduction counting and handling lists/sets. These tasks are challenging on their own and even more demanding when the required facts are scattered across long natural text. Our evaluations show that popular LLMs effectively utilize only 1045;2037; of the context and their performance declines sharply with increased reasoning complexity. Among alternatives to in45;context reasoning Retrieval45;Augmented Generation methods achieve a modest 6037; accuracy on single45;fact question answering independent of context length. Among context extension methods the highest performance is demonstrated by recurrent memory transformers enabling the processing of lengths up to 11 million tokens. The BABILong benchmark is extendable to any length to support the evaluation of new upcoming models with increased capabilities and we provide splits up to 1 million token lengths.
