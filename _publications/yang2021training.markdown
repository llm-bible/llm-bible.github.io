---
layout: publication
title: "NT5?! Training T5 To Perform Numerical Reasoning"
authors: Yang Peng-jian, Chen Ying Ting, Chen Yuechan, Cer Daniel
conference: "Arxiv"
year: 2021
bibkey: yang2021training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2104.07307"}
tags: ['BERT', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques']
---
Numerical reasoning over text (NRoT) presents unique challenges that are not well addressed by existing pre-training objectives. We explore five sequential training schedules that adapt a pre-trained T5 model for NRoT. Our final model is adapted from T5 but further pre-trained on three datasets designed to strengthen skills necessary for NRoT and general reading comprehension before being fine-tuned on the Discrete Reasoning over Text (DROP) dataset. The training improves DROPs adjusted F1 performance (a numeracy-focused score) from 45.90 to 70.83. Our model closes in on GenBERT (72.4) a custom BERT-Base model using the same datasets with significantly more parameters. We show that training the T5 multitasking framework with multiple numerical reasoning datasets of increasing difficulty good performance on DROP can be achieved without manually engineering partitioned functionality between distributed and symbol modules.
