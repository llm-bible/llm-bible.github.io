---
layout: publication
title: 'Smi-editor: Edit-based SMILES Language Model With Fragment-level Supervision'
authors: Kangjie Zheng, Siyue Liang, Junwei Yang, Bin Feng, Zequn Liu, Wei Ju, Zhiping Xiao, Ming Zhang
conference: "Arxiv"
year: 2024
bibkey: zheng2024smi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.05569"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'Pre-Training', 'Attention Mechanism']
---
SMILES, a crucial textual representation of molecular structures, has
garnered significant attention as a foundation for pre-trained language models
(LMs). However, most existing pre-trained SMILES LMs focus solely on the
single-token level supervision during pre-training, failing to fully leverage
the substructural information of molecules. This limitation makes the
pre-training task overly simplistic, preventing the models from capturing
richer molecular semantic information. Moreover, during pre-training, these
SMILES LMs only process corrupted SMILES inputs, never encountering any valid
SMILES, which leads to a train-inference mismatch. To address these challenges,
we propose SMI-Editor, a novel edit-based pre-trained SMILES LM. SMI-Editor
disrupts substructures within a molecule at random and feeds the resulting
SMILES back into the model, which then attempts to restore the original SMILES
through an editing process. This approach not only introduces fragment-level
training signals, but also enables the use of valid SMILES as inputs, allowing
the model to learn how to reconstruct complete molecules from these incomplete
structures. As a result, the model demonstrates improved scalability and an
enhanced ability to capture fragment-level molecular information. Experimental
results show that SMI-Editor achieves state-of-the-art performance across
multiple downstream molecular tasks, and even outperforming several 3D
molecular representation models.
