---
layout: publication
title: 'Democratizing Large Language Model-based Graph Data Augmentation Via Latent Knowledge Graphs'
authors: Yushi Feng, Tsai Hor Chan, Guosheng Yin, Lequan Yu
conference: "Arxiv"
year: 2025
bibkey: feng2025democratizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.13555"}
tags: ['Fine-Tuning', 'Applications', 'Interpretability and Explainability', 'RAG', 'Reinforcement Learning', 'Merging', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Data augmentation is necessary for graph representation learning due to the
scarcity and noise present in graph data. Most of the existing augmentation
methods overlook the context information inherited from the dataset as they
rely solely on the graph structure for augmentation. Despite the success of
some large language model-based (LLM) graph learning methods, they are mostly
white-box which require access to the weights or latent features from the
open-access LLMs, making them difficult to be democratized for everyone as
existing LLMs are mostly closed-source for commercial considerations. To
overcome these limitations, we propose a black-box context-driven graph data
augmentation approach, with the guidance of LLMs -- DemoGraph. Leveraging the
text prompt as context-related information, we task the LLM with generating
knowledge graphs (KGs), which allow us to capture the structural interactions
from the text outputs. We then design a dynamic merging schema to
stochastically integrate the LLM-generated KGs into the original graph during
training. To control the sparsity of the augmented graph, we further devise a
granularity-aware prompting strategy and an instruction fine-tuning module,
which seamlessly generates text prompts according to different granularity
levels of the dataset. Extensive experiments on various graph learning tasks
validate the effectiveness of our method over existing graph data augmentation
methods. Notably, our approach excels in scenarios involving electronic health
records (EHRs), which validates its maximal utilization of contextual
knowledge, leading to enhanced predictive performance and interpretability.
