---
layout: publication
title: 'Gl-fusion: Rethinking The Combination Of Graph Neural Network And Large Language Model'
authors: Haotong Yang, Xiyuan Wang, Qian Tao, Shuxian Hu, Zhouchen Lin, Muhan Zhang
conference: "Arxiv"
year: 2024
bibkey: yang2024gl
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.06849"}
tags: ['Transformer', 'GPT', 'Model Architecture', 'Merging', 'Attention Mechanism', 'Pretraining Methods', 'Arxiv']
---
Recent research on integrating Large Language Models (LLMs) with Graph Neural
Networks (GNNs) typically follows two approaches: LLM-centered models, which
convert graph data into tokens for LLM processing, and GNN-centered models,
which use LLMs to encode text features into node and edge representations for
GNN input. LLM-centered models often struggle to capture graph structures
effectively, while GNN-centered models compress variable-length textual data
into fixed-size vectors, limiting their ability to understand complex
semantics. Additionally, GNN-centered approaches require converting tasks into
a uniform, manually-designed format, restricting them to classification tasks
and preventing language output. To address these limitations, we introduce a
new architecture that deeply integrates GNN with LLM, featuring three key
innovations: (1) Structure-Aware Transformers, which incorporate GNN's
message-passing capabilities directly into LLM's transformer layers, allowing
simultaneous processing of textual and structural information and generating
outputs from both GNN and LLM; (2) Graph-Text Cross-Attention, which processes
full, uncompressed text from graph nodes and edges, ensuring complete semantic
integration; and (3) GNN-LLM Twin Predictor, enabling LLM's flexible
autoregressive generation alongside GNN's scalable one-pass prediction.
GL-Fusion achieves outstand performance on various tasks. Notably, it achieves
state-of-the-art performance on OGBN-Arxiv and OGBG-Code2.
