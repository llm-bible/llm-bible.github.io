---
layout: publication
title: Murag\: Multimodal Retrieval-augmented Generator For Open Question Answering Over Images And Text
authors: Chen Wenhu, Hu Hexiang, Chen Xi, Verga Pat, Cohen William W.
conference: "Arxiv"
year: 2022
bibkey: chen2022multimodal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.02928"}
tags: ['Applications', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Transformer']
---
While language Models store a massive amount of world knowledge implicitly in their parameters even very large models often fail to encode information about rare entities and events while incurring huge computational costs. Recently retrieval-augmented models such as REALM RAG and RETRO have incorporated world knowledge into language generation by leveraging an external non-parametric index and have demonstrated impressive performance with constrained model sizes. However these methods are restricted to retrieving only textual knowledge neglecting the ubiquitous amount of knowledge in other modalities like images -- much of which contains information not covered by any text. To address this limitation we propose the first Multimodal Retrieval-Augmented Transformer (MuRAG) which accesses an external non-parametric multimodal memory to augment language generation. MuRAG is pre-trained with a mixture of large-scale image-text and text-only corpora using a joint contrastive and generative loss. We perform experiments on two different datasets that require retrieving and reasoning over both images and text to answer a given query WebQA and MultimodalQA. Our results show that MuRAG achieves state-of-the-art accuracy outperforming existing models by 10-2037; absolute on both datasets and under both distractor and full-wiki settings.
