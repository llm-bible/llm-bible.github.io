---
layout: publication
title: 'SAIL: Sample-centric In-context Learning For Document Information Extraction'
authors: Jinyu Zhang, Zhiyuan You, Jize Wang, Xinyi Le
conference: "Arxiv"
year: 2024
bibkey: zhang2024sample
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.17092"}
tags: ['RAG', 'Training Techniques', 'Prompting', 'In-Context Learning']
---
Document Information Extraction (DIE) aims to extract structured information
from Visually Rich Documents (VRDs). Previous full-training approaches have
demonstrated strong performance but may struggle with generalization to unseen
data. In contrast, training-free methods leverage powerful pre-trained models
like Large Language Models (LLMs) to address various downstream tasks with only
a few examples. Nonetheless, training-free methods for DIE encounter two
primary challenges: (1) understanding the complex relationship between layout
and textual elements in VRDs, and (2) providing accurate guidance to
pre-trained models. To address these challenges, we propose Sample-centric
In-context Learning (SAIL) for DIE. SAIL introduces a fine-grained entity-level
textual similarity to facilitate in-depth text analysis by LLMs and
incorporates layout similarity to enhance the analysis of layouts in VRDs.
Additionally, SAIL formulates a unified In-Context Learning (ICL) prompt
template for various sample-centric examples, enabling tailored prompts that
deliver precise guidance to pre-trained models for each sample. Extensive
experiments on FUNSD, CORD, and SROIE benchmarks with various base models
(e.g., LLMs) indicate that our method outperforms training-free baselines, even
closer to the full-training methods. The results show the superiority and
generalization of our method.
