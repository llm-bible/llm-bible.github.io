---
layout: publication
title: 'Idt5: Indonesian Version Of Multilingual T5 Transformer'
authors: Mukhlish Fuadi, Adhi Dharma Wibawa, Surya Sumpeno
conference: "Arxiv"
year: 2023
bibkey: fuadi2023indonesian
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2302.00856'}
tags: ['Transformer', 'Model Architecture', 'Applications', 'Tools', 'Reinforcement Learning', 'Pretraining Methods']
---
Indonesian language is spoken by almost 200 million people and is the 10th
most spoken language in the world, but it is under-represented in NLP (Natural
Language Processing) research. A sparsity of language resources has hampered
previous work on Indonesian. The Transformer is a new architecture rapidly
becoming dominant for NLP, surpassing alternatives like convolutional and
recurrent neural networks. T5 (Text-to-Text Transfer Transformer) is a
Transformer model that converts all text-based language problems to
text-to-text format for English. The multilingual variant is mT5 (multilingual
T5) which has shown promising results on many NLP tasks across languages.
However, the size of this multilingual model is a drawback for its application
in real production applications, which sometimes require only one language. In
this study, the mT5 model was adapted for only one language, Indonesian,
resulting in a pre-trained T5 model that was specific only for Indonesian with
a smaller size. For performance comparison, we fine-tuned this model and the
mT5 model to the Sentiment Analysis (SA), Question Generation (QG), and
Question Answering (QA) tasks with the exact mechanism and dataset. Fine-tuned
model based on our model achieved 77.18% accuracy on SA, 8% higher than the
mT5-based model, and obtained nearly the same score as the mT5-based model on
QG and QA. The results confirm that it is possible to produce a smaller
pre-trained model that maintains comparable yields while reducing the model
size by up to 58%. In addition, the resulting model requires less memory, loads
faster, and inference times faster.
