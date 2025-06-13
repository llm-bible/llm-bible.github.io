---
layout: publication
title: 'Do We Still Need Human Annotators? Prompting Large Language Models For Aspect Sentiment Quad Prediction'
authors: Nils Constantin Hellwig, Jakob Fehle, Udo Kruschwitz, Christian Wolff
conference: "Arxiv"
year: 2025
bibkey: hellwig2025do
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.13044'}
tags: ['Few-Shot', 'Prompting', 'Training Techniques']
---
Aspect sentiment quad prediction (ASQP) facilitates a detailed understanding of opinions expressed in a text by identifying the opinion term, aspect term, aspect category and sentiment polarity for each opinion. However, annotating a full set of training examples to fine-tune models for ASQP is a resource-intensive process. In this study, we explore the capabilities of large language models (LLMs) for zero- and few-shot learning on the ASQP task across five diverse datasets. We report F1 scores almost up to par with those obtained with state-of-the-art fine-tuned models and exceeding previously reported zero- and few-shot performance. In the 20-shot setting on the Rest16 restaurant domain dataset, LLMs achieved an F1 score of 51.54, compared to 60.39 by the best-performing fine-tuned method MVP. Additionally, we report the performance of LLMs in target aspect sentiment detection (TASD), where the F1 scores were close to fine-tuned models, achieving 68.93 on Rest16 in the 30-shot setting, compared to 72.76 with MVP. While human annotators remain essential for achieving optimal performance, LLMs can reduce the need for extensive manual annotation in ASQP tasks.
