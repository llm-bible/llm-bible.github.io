---
layout: publication
title: "On Training Instance Selection For Few-shot Neural Text Generation"
authors: Chang Ernie, Shen Xiaoyu, Yeh Hui-syuan, Demberg Vera
conference: "Arxiv"
year: 2021
bibkey: chang2021training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2107.03176"}
tags: ['Applications', 'Attention Mechanism', 'Few Shot', 'Language Modeling', 'Model Architecture', 'Training Techniques']
---
Large-scale pretrained language models have led to dramatic improvements in text generation. Impressive performance can be achieved by finetuning only on a small number of instances (few-shot setting). Nonetheless almost all previous work simply applies random sampling to select the few-shot training instances. Little to no attention has been paid to the selection strategies and how they would affect model performance. In this work we present a study on training instance selection in few-shot neural text generation. The selection decision is made based only on the unlabeled data so as to identify the most worthwhile data points that should be annotated under some budget of labeling cost. Based on the intuition that the few-shot training instances should be diverse and representative of the entire data distribution we propose a simple selection strategy with K-means clustering. We show that even with the naive clustering-based approach the generation models consistently outperform random sampling on three text generation tasks data-to-text generation document summarization and question generation. We hope that this work will call for more attention on this largely unexplored area.
