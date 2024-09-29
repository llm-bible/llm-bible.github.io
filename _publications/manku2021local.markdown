---
layout: publication
title: Local And Global Context-based Pairwise Models For Sentence Ordering
authors: Manku Ruskin Raj, Paul Aditya Jyoti
conference: "Knowledge-Based Systems Volume"
year: 2021
bibkey: manku2021local
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2110.04291"}
tags: ['BERT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
Sentence Ordering refers to the task of rearranging a set of sentences into the appropriate coherent order. For this task most previous approaches have explored global context-based end-to-end methods using Sequence Generation techniques. In this paper we put forward a set of robust local and global context-based pairwise ordering strategies leveraging which our prediction strategies outperform all previous works in this domain. Our proposed encoding method utilizes the paragraphs rich global contextual information to predict the pairwise order using novel transformer architectures. Analysis of the two proposed decoding strategies helps better explain error propagation in pairwise models. This approach is the most accurate pure pairwise model and our encoding strategy also significantly improves the performance of other recent approaches that use pairwise models including the previous state-of-the-art demonstrating the research novelty and generalizability of this work. Additionally we show how the pre-training task for ALBERT helps it to significantly outperform BERT despite having considerably lesser parameters. The extensive experimental results architectural analysis and ablation studies demonstrate the effectiveness and superiority of the proposed models compared to the previous state-of-the-art besides providing a much better understanding of the functioning of pairwise models.
