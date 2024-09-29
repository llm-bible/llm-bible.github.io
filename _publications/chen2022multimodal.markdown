---
layout: publication
title: Murag Multimodal Retrieval45;augmented Generator For Open Question Answering Over Images And Text
authors: Chen Wenhu, Hu Hexiang, Chen Xi, Verga Pat, Cohen William W.
conference: "Arxiv"
year: 2022
bibkey: chen2022multimodal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.02928"}
tags: ['Applications', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Transformer']
---
While language Models store a massive amount of world knowledge implicitly in their parameters even very large models often fail to encode information about rare entities and events while incurring huge computational costs. Recently retrieval45;augmented models such as REALM RAG and RETRO have incorporated world knowledge into language generation by leveraging an external non45;parametric index and have demonstrated impressive performance with constrained model sizes. However these methods are restricted to retrieving only textual knowledge neglecting the ubiquitous amount of knowledge in other modalities like images 45;45; much of which contains information not covered by any text. To address this limitation we propose the first Multimodal Retrieval45;Augmented Transformer (MuRAG) which accesses an external non45;parametric multimodal memory to augment language generation. MuRAG is pre45;trained with a mixture of large45;scale image45;text and text45;only corpora using a joint contrastive and generative loss. We perform experiments on two different datasets that require retrieving and reasoning over both images and text to answer a given query WebQA and MultimodalQA. Our results show that MuRAG achieves state45;of45;the45;art accuracy outperforming existing models by 1045;2037; absolute on both datasets and under both distractor and full45;wiki settings.
