---
layout: publication
title: Synthetic Dataset Creation and Fine-Tuning of Transformer Models for Question Answering in Serbian
authors: Cvetanović Aleksa, Tadić Predrag
conference: "Arxiv"
year: 2024
bibkey: cvetanović2024synthetic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.08617"}
tags: ['ARXIV', 'Applications', 'BERT', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
In this paper we focus on generating a synthetic question answering (QA) dataset using an adapted Translate-Align-Retrieve method. Using this method we created the largest Serbian QA dataset of more than 87K samples which we name SQuAD-sr. To acknowledge the script duality in Serbian we generated both Cyrillic and Latin versions of the dataset. We investigate the dataset quality and use it to fine-tune several pre-trained QA models. Best results were obtained by fine-tuning the BERTic model on our Latin SQuAD-sr dataset achieving 73.91 Exact Match and 82.97 F1 score on the benchmark XQuAD dataset which we translated into Serbian for the purpose of evaluation. The results show that our model exceeds zero-shot baselines but fails to go beyond human performance. We note the advantage of using a monolingual pre-trained model over multilingual as well as the performance increase gained by using Latin over Cyrillic. By performing additional analysis we show that questions about numeric values or dates are more likely to be answered correctly than other types of questions. Finally we conclude that SQuAD-sr is of sufficient quality for fine-tuning a Serbian QA model in the absence of a manually crafted and annotated dataset.
