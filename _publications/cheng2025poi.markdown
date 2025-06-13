---
layout: publication
title: 'Poi-enhancer: An Llm-based Semantic Enhancement Framework For POI Representation Learning'
authors: Jiawei Cheng, Jingyuan Wang, Yichuan Zhang, Jiahao Ji, Yuanshao Zhu, Zhibo Zhang, Xiangyu Zhao
conference: "Arxiv"
year: 2025
bibkey: cheng2025poi
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.10038'}
tags: ['Attention Mechanism', 'RAG', 'Model Architecture', 'Tools', 'Merging', 'Prompting', 'Multimodal Models', 'Reinforcement Learning', 'Pretraining Methods']
---
POI representation learning plays a crucial role in handling tasks related to
user mobility data. Recent studies have shown that enriching POI
representations with multimodal information can significantly enhance their
task performance. Previously, the textual information incorporated into POI
representations typically involved only POI categories or check-in content,
leading to relatively weak textual features in existing methods. In contrast,
large language models (LLMs) trained on extensive text data have been found to
possess rich textual knowledge. However leveraging such knowledge to enhance
POI representation learning presents two key challenges: first, how to extract
POI-related knowledge from LLMs effectively, and second, how to integrate the
extracted information to enhance POI representations. To address these
challenges, we propose POI-Enhancer, a portable framework that leverages LLMs
to improve POI representations produced by classic POI learning models. We
first design three specialized prompts to extract semantic information from
LLMs efficiently. Then, the Dual Feature Alignment module enhances the quality
of the extracted information, while the Semantic Feature Fusion module
preserves its integrity. The Cross Attention Fusion module then fully
adaptively integrates such high-quality information into POI representations
and Multi-View Contrastive Learning further injects human-understandable
semantic information into these representations. Extensive experiments on three
real-world datasets demonstrate the effectiveness of our framework, showing
significant improvements across all baseline representations.
