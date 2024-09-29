---
layout: publication
title: Big Bidirectional Insertion Representations For Documents
authors: Li Lala, Chan William
conference: "Arxiv"
year: 2019
bibkey: li2019big
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1910.13034"}
tags: ['Applications', 'Attention Mechanism', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
The Insertion Transformer is well suited for long form text generation due to its parallel generation capabilities requiring O(log_2 n) generation steps to generate n tokens. However modeling long sequences is difficult as there is more ambiguity captured in the attention mechanism. This work proposes the Big Bidirectional Insertion Representations for Documents (Big BIRD) an insertion-based model for document-level translation tasks. We scale up the insertion-based models to long form documents. Our key contribution is introducing sentence alignment via sentence-positional embeddings between the source and target document. We show an improvement of +4.3 BLEU on the WMT19 English→German document-level translation task compared with the Insertion Transformer baseline.
