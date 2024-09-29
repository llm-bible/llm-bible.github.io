---
layout: publication
title: Unitrec A Unified Text-to-text Transformer And Joint Contrastive Learning Framework For Text-based Recommendation
authors: Mao Zhiming, Wang Huimin, Du Yiming, Wong Kam-fai
conference: "Arxiv"
year: 2023
bibkey: mao2023unified
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.15756"}
  - {name: "Code", url: "https://github.com/Veason-silverbullet/UniTRec"}
tags: ['Attention Mechanism', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Tools', 'Transformer']
---
Prior study has shown that pretrained language models (PLM) can boost the performance of text-based recommendation. In contrast to previous works that either use PLM to encode user history as a whole input text or impose an additional aggregation network to fuse multi-turn history representations we propose a unified local- and global-attention Transformer encoder to better model two-level contexts of user history. Moreover conditioned on user history encoded by Transformer encoders our framework leverages Transformer decoders to estimate the language perplexity of candidate text items which can serve as a straightforward yet significant contrastive signal for user-item text matching. Based on this our framework UniTRec unifies the contrastive objectives of discriminative matching scores and candidate text perplexity to jointly enhance text-based recommendation. Extensive evaluation shows that UniTRec delivers SOTA performance on three text-based recommendation tasks. Code is available at https://github.com/Veason-silverbullet/UniTRec."
