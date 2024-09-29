---
layout: publication
title: 'MMICT: Boosting Multi-modal Fine-tuning With In-context Examples'
authors: Chen Tao, Zhang Enwei, Gao Yuting, Li Ke, Sun Xing, Zhang Yan, Li Hui, Ji Rongrong
conference: "Arxiv"
year: 2023
bibkey: chen2023boosting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.06363"}
  - {name: "Code", url: "https://github.com/KDEGroup/MMICT"}
tags: ['Fine Tuning', 'Has Code', 'In Context Learning', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques']
---
Although In-Context Learning (ICL) brings remarkable performance gains to Large Language Models (LLMs) the improvements remain lower than fine-tuning on downstream tasks. This paper introduces Multi-Modal In-Context Tuning (MMICT) a novel multi-modal fine-tuning paradigm that boosts multi-modal fine-tuning by fully leveraging the promising ICL capability of multi-modal LLMs (MM-LLMs). We propose the Multi-Modal Hub (M-Hub) a unified module that captures various multi-modal features according to different inputs and objectives. Based on M-Hub MMICT enables MM-LLMs to learn from in-context visual-guided textual features and subsequently generate outputs conditioned on the textual-guided visual features. Moreover leveraging the flexibility of M-Hub we design a variety of in-context demonstrations. Extensive experiments on a diverse range of downstream multi-modal tasks demonstrate that MMICT significantly outperforms traditional fine-tuning strategy and the vanilla ICT method that directly takes the concatenation of all information from different modalities as input. Our implementation is available at https://github.com/KDEGroup/MMICT."
