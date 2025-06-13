---
layout: publication
title: 'Mala-500: Massive Language Adaptation Of Large Language Models'
authors: Peiqin Lin, Shaoxiong Ji, Jörg Tiedemann, André F. T. Martins, Hinrich Schütze
conference: "Arxiv"
year: 2024
bibkey: lin2024mala
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2401.13303'}
tags: ['RAG', 'Training Techniques', 'Prompting', 'In-Context Learning', 'Pretraining Methods']
---
Large language models (LLMs) have advanced the state of the art in natural
language processing. However, their predominant design for English or a limited
set of languages creates a substantial gap in their effectiveness for
low-resource languages. To bridge this gap, we introduce MaLA-500, a novel
large language model designed to cover an extensive range of 534 languages. To
train MaLA-500, we employ vocabulary extension and continued pretraining on
LLaMA 2 with Glot500-c. Our intrinsic evaluation demonstrates that MaLA-500 is
better at predicting the given texts of low-resource languages than existing
multilingual LLMs. Moreover, the extrinsic evaluation of in-context learning
shows that MaLA-500 outperforms previous LLMs on SIB200 and Taxi1500 by a
significant margin, i.e., 11.68% and 4.82% marco-average accuracy across
languages. We release MaLA-500 at https://huggingface.co/MaLA-LM
