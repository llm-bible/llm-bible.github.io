---
layout: publication
title: 'Gt2vec: Large Language Models As Multi-modal Encoders For Text And Graph-structured Data'
authors: Jiacheng Lin, Kun Qian, Haoyu Han, Nurendra Choudhary, Tianxin Wei, Zhongruo Wang, Sahika Genc, Edward W Huang, Sheng Wang, Karthik Subbian, Danai Koutra, Jimeng Sun
conference: "Arxiv"
year: 2024
bibkey: lin2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.11235"}
tags: ['Transformer', 'Tools', 'Applications', 'RAG', 'Model Architecture', 'Pretraining Methods']
---
Graph-structured information offers rich contextual information that can
enhance language models by providing structured relationships and hierarchies,
leading to more expressive embeddings for various applications such as
retrieval, question answering, and classification. However, existing methods
for integrating graph and text embeddings, often based on Multi-layer
Perceptrons (MLPs) or shallow transformers, are limited in their ability to
fully exploit the heterogeneous nature of these modalities. To overcome this,
we propose GT2Vec, a simple yet effective framework that leverages Large
Language Models (LLMs) to jointly encode text and graph data. Specifically,
GT2Vec employs an MLP adapter to project graph embeddings into the same space
as text embeddings, allowing the LLM to process both modalities jointly. Unlike
prior work, we also introduce contrastive learning to align the graph and text
spaces more effectively, thereby improving the quality of learned joint
embeddings. Empirical results across six datasets spanning three tasks,
knowledge graph-contextualized question answering, graph-text pair
classification, and retrieval, demonstrate that GT2Vec consistently outperforms
existing baselines, achieving significant improvements across multiple
datasets. These results highlight GT2Vec's effectiveness in integrating graph
and text data. Ablation studies further validate the effectiveness of our
method.
