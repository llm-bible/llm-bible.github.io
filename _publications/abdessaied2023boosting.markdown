---
layout: publication
title: VD45;GR Boosting visual dialog With Cascaded Spatial45;temporal Multi45;modal graphs
authors: Abdessaied Adnen, Shi Lei, Bulling Andreas
conference: "Arxiv"
year: 2023
bibkey: abdessaied2023boosting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.16590"}
tags: ['Attention Mechanism', 'BERT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning']
---
We propose VD45;GR 45; a novel visual dialog model that combines pre45;trained language models (LMs) with graph neural networks (GNNs). Prior works mainly focused on one class of models at the expense of the other thus missing out on the opportunity of combining their respective benefits. At the core of VD45;GR is a novel integration mechanism that alternates between spatial45;temporal multi45;modal GNNs and BERT layers and that covers three distinct contributions First we use multi45;modal GNNs to process the features of each modality (image question and dialog history) and exploit their local structures before performing BERT global attention. Second we propose hub45;nodes that link to all other nodes within one modality graph allowing the model to propagate information from one GNN (modality) to the other in a cascaded manner. Third we augment the BERT hidden states with fine45;grained multi45;modal GNN features before passing them to the next VD45;GR layer. Evaluations on VisDial v1.0 VisDial v0.9 VisDialConv and VisPro show that VD45;GR achieves new state45;of45;the45;art results across all four datasets.
