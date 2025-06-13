---
layout: publication
title: 'Hat5: Hate Language Identification Using Text-to-text Transfer Transformer'
authors: Sana Sabah Sabry, Tosin Adewumi, Nosheen Abid, György Kovacs, Foteini Liwicki, Marcus Liwicki
conference: "Arxiv"
year: 2022
bibkey: sabry2022hate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2202.05690"}
tags: ['Transformer', 'GPT', 'Ethics and Bias', 'Model Architecture', 'Interpretability', 'Training Techniques', 'Pretraining Methods']
---
We investigate the performance of a state-of-the art (SoTA) architecture T5
(available on the SuperGLUE) and compare with it 3 other previous SoTA
architectures across 5 different tasks from 2 relatively diverse datasets. The
datasets are diverse in terms of the number and types of tasks they have. To
improve performance, we augment the training data by using an autoregressive
model. We achieve near-SoTA results on a couple of the tasks - macro F1 scores
of 81.66% for task A of the OLID 2019 dataset and 82.54% for task A of the hate
speech and offensive content (HASOC) 2021 dataset, where SoTA are 82.9% and
83.05%, respectively. We perform error analysis and explain why one of the
models (Bi-LSTM) makes the predictions it does by using a publicly available
algorithm: Integrated Gradient (IG). This is because explainable artificial
intelligence (XAI) is essential for earning the trust of users. The main
contributions of this work are the implementation method of T5, which is
discussed; the data augmentation using a new conversational AI model
checkpoint, which brought performance improvements; and the revelation on the
shortcomings of HASOC 2021 dataset. It reveals the difficulties of poor data
annotation by using a small set of examples where the T5 model made the correct
predictions, even when the ground truth of the test set were incorrect (in our
opinion). We also provide our model checkpoints on the HuggingFace hub1 to
foster transparency.
