---
layout: publication
title: 'Transformer Language Models Handle Word Frequency In Prediction Head'
authors: Kobayashi Goro, Kuribayashi Tatsuki, Yokoi Sho, Inui Kentaro
conference: "Arxiv"
year: 2023
bibkey: kobayashi2023transformer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.18294"}
tags: ['Applications', 'BERT', 'Ethics And Bias', 'GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Transformer']
---
Prediction head is a crucial component of Transformer language models. Despite its direct impact on prediction, this component has often been overlooked in analyzing Transformers. In this study, we investigate the inner workings of the prediction head, specifically focusing on bias parameters. Our experiments with BERT and GPT-2 models reveal that the biases in their word prediction heads play a significant role in the models' ability to reflect word frequency in a corpus, aligning with the logit adjustment method commonly used in long-tailed learning. We also quantify the effect of controlling the biases in practical auto-regressive text generation scenarios; under a particular setting, more diverse text can be generated without compromising text quality.
