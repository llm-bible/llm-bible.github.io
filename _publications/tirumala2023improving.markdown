---
layout: publication
title: D4 Improving LLM Pretraining Via Document De45;duplication And Diversification
authors: Tirumala Kushal, Simig Daniel, Aghajanyan Armen, Morcos Ari S.
conference: "Arxiv"
year: 2023
bibkey: tirumala2023improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.12284"}
tags: ['Efficiency And Optimization', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Over recent years an increasing amount of compute and data has been poured into training large language models (LLMs) usually by doing one45;pass learning on as many tokens as possible randomly selected from large45;scale web corpora. While training on ever45;larger portions of the internet leads to consistent performance improvements the size of these improvements diminishes with scale and there has been little work exploring the effect of data selection on pre45;training and downstream performance beyond simple de45;duplication methods such as MinHash. Here we show that careful data selection (on top of de45;duplicated data) via pre45;trained model embeddings can speed up training (2037; efficiency gains) and improves average downstream accuracy on 16 NLP tasks (up to 237;) at the 6.7B model scale. Furthermore we show that repeating data intelligently consistently outperforms baseline training (while repeating random data performs worse than baseline training). Our results indicate that clever data selection can significantly improve LLM pre45;training calls into question the common practice of training for a single epoch on as much data as possible and demonstrates a path to keep improving our models past the limits of randomly sampling web data.
