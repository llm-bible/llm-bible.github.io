---
layout: publication
title: VD45;BERT A Unified Vision And Dialog Transformer With BERT
authors: Wang Yue, Joty Shafiq, Lyu Michael R., King Irwin, Xiong Caiming, Hoi Steven C. H.
conference: "Arxiv"
year: 2020
bibkey: wang2020vd
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2004.13278"}
  - {name: "Code", url: "https://github.com/salesforce/VD&#45;BERT"}
tags: ['Agentic', 'Attention Mechanism', 'BERT', 'Has Code', 'Merging', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques', 'Transformer']
---
Visual dialog is a challenging vision45;language task where a dialog agent needs to answer a series of questions through reasoning on the image content and dialog history. Prior work has mostly focused on various attention mechanisms to model such intricate interactions. By contrast in this work we propose VD45;BERT a simple yet effective framework of unified vision45;dialog Transformer that leverages the pretrained BERT language models for Visual Dialog tasks. The model is unified in that (1) it captures all the interactions between the image and the multi45;turn dialog using a single45;stream Transformer encoder and (2) it supports both answer ranking and answer generation seamlessly through the same architecture. More crucially we adapt BERT for the effective fusion of vision and dialog contents via visually grounded training. Without the need of pretraining on external vision45;language data our model yields new state of the art achieving the top position in both single45;model and ensemble settings (74.54 and 75.35 NDCG scores) on the visual dialog leaderboard. Our code and pretrained models are released at https://github.com/salesforce/VD&#45;BERT.
