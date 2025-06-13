---
layout: publication
title: 'Efficient Pre-training For Localized Instruction Generation Of Videos'
authors: Anil Batra, Davide Moltisanti, Laura Sevilla-lara, Marcus Rohrbach, Frank Keller
conference: "Arxiv"
year: 2023
bibkey: batra2023efficient
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2311.15964'}
tags: ['Transformer', 'RAG', 'Training Techniques', 'Model Architecture', 'Pre-Training', 'Pretraining Methods']
---
Procedural videos, exemplified by recipe demonstrations, are instrumental in
conveying step-by-step instructions. However, understanding such videos is
challenging as it involves the precise localization of steps and the generation
of textual instructions. Manually annotating steps and writing instructions is
costly, which limits the size of current datasets and hinders effective
learning. Leveraging large but noisy video-transcript datasets for pre-training
can boost performance but demands significant computational resources.
Furthermore, transcripts contain irrelevant content and differ in style from
human-written instructions. To mitigate these issues, we propose a novel
technique, Sieve-&-Swap, to automatically generate high-quality training data
for the recipe domain: (i) Sieve: filters irrelevant transcripts and (ii) Swap:
acquires high-quality text by replacing transcripts with human-written
instruction from a text-only recipe dataset. The resulting dataset is three
orders of magnitude smaller than current web-scale datasets but enables
efficient training of large-scale models. Alongside Sieve-&-Swap, we propose
Procedure Transformer (ProcX), a model for end-to-end step localization and
instruction generation for procedural videos. When pre-trained on our curated
dataset, this model achieves state-of-the-art performance on YouCook2 and Tasty
while using a fraction of the training data. We have released code and dataset.
