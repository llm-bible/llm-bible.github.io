---
layout: publication
title: MMICT Boosting Multi45;modal Fine45;tuning With In45;context Examples
authors: Chen Tao, Zhang Enwei, Gao Yuting, Li Ke, Sun Xing, Zhang Yan, Li Hui, Ji Rongrong
conference: "Arxiv"
year: 2023
bibkey: chen2023boosting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.06363"}
  - {name: "Code", url: "https://github.com/KDEGroup/MMICT"}
tags: ['Has Code', 'Prompting', 'RAG']
---
Although In45;Context Learning (ICL) brings remarkable performance gains to Large Language Models (LLMs) the improvements remain lower than fine45;tuning on downstream tasks. This paper introduces Multi45;Modal In45;Context Tuning (MMICT) a novel multi45;modal fine45;tuning paradigm that boosts multi45;modal fine45;tuning by fully leveraging the promising ICL capability of multi45;modal LLMs (MM45;LLMs). We propose the Multi45;Modal Hub (M45;Hub) a unified module that captures various multi45;modal features according to different inputs and objectives. Based on M45;Hub MMICT enables MM45;LLMs to learn from in45;context visual45;guided textual features and subsequently generate outputs conditioned on the textual45;guided visual features. Moreover leveraging the flexibility of M45;Hub we design a variety of in45;context demonstrations. Extensive experiments on a diverse range of downstream multi45;modal tasks demonstrate that MMICT significantly outperforms traditional fine45;tuning strategy and the vanilla ICT method that directly takes the concatenation of all information from different modalities as input. Our implementation is available at https://github.com/KDEGroup/MMICT.
