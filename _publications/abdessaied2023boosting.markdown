---
layout: publication
title: ()-() Boosting ()isual ()ialog With Cascaded Spatial-temporal Multi-modal ()aphs
authors: Abdessaied Adnen, Shi Lei, Bulling Andreas
conference: "Arxiv"
year: 2023
bibkey: abdessaied2023boosting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.16590"}
tags: ['Attention Mechanism', 'BERT', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning']
---
We propose (mathbbVD)-(mathbbGR) - a novel visual dialog model that combines pre-trained language models (LMs) with graph neural networks (GNNs). Prior works mainly focused on one class of models at the expense of the other thus missing out on the opportunity of combining their respective benefits. At the core of (mathbbVD)-(mathbbGR) is a novel integration mechanism that alternates between spatial-temporal multi-modal GNNs and BERT layers and that covers three distinct contributions First we use multi-modal GNNs to process the features of each modality (image question and dialog history) and exploit their local structures before performing BERT global attention. Second we propose hub-nodes that link to all other nodes within one modality graph allowing the model to propagate information from one GNN (modality) to the other in a cascaded manner. Third we augment the BERT hidden states with fine-grained multi-modal GNN features before passing them to the next (mathbbVD)-(mathbbGR) layer. Evaluations on VisDial v1.0 VisDial v0.9 VisDialConv and VisPro show that (mathbbVD)-(mathbbGR) achieves new state-of-the-art results across all four datasets.
