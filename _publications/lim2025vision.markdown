---
layout: publication
title: 'VLMT: Vision-language Multimodal Transformer For Multimodal Multi-hop Question Answering'
authors: Qi Zhi Lim, Chin Poo Lee, Kian Ming Lim, Kalaiarasi Sonai Muthu Anbananthen
conference: "Arxiv"
year: 2025
bibkey: lim2025vision
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.08269"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Pretraining Methods', 'Transformer', 'Applications']
---
The increasing availability of multimodal data across text, tables, and
images presents new challenges for developing models capable of complex
cross-modal reasoning. Existing methods for Multimodal Multi-hop Question
Answering (MMQA) often suffer from limited reasoning capabilities, reliance on
modality conversion, and inadequate alignment between visual and textual
representations. To address these limitations, this paper introduces
Vision-Language Multimodal Transformer (VLMT), a unified architecture that
integrates a transformer-based vision encoder with a sequence-to-sequence
language model. VLMT employs a direct token-level injection mechanism to fuse
visual and textual inputs within a shared embedding space, eliminating the need
for intermediate projection layers. To enhance cross-modal alignment and
reasoning, a three-stage pretraining strategy is proposed to progressively
align vision-language representations and improve the model's capacity for
multimodal understanding. Based on the pretrained backbone, two task-specific
modules are instantiated to form a two-stage MMQA framework: a multimodal
reranker that predicts document relevance scores and utilizes a relative
threshold with top-k strategy for context retrieval, and a multimodal question
answering model that generates contextually grounded answers based on the
retrieved evidence. Comprehensive experiments on two benchmark datasets
demonstrate the effectiveness of the proposed approach. On MultimodalQA
validation set, VLMT-Large achieves 76.5% Exact Match and 80.1% F1,
outperforming the previous state-of-the-art by +9.1% in Exact Match and +8.8%
in F1. On WebQA, it attains a QA score of 47.6, surpassing prior models such as
PERQA by +3.2. These results highlight VLMT's strong capabilities in multimodal
reasoning and its potential to advance real-world information retrieval and
question answering systems.
