---
layout: publication
title: 'EMMA: Efficient Visual Alignment In Multi-modal Llms'
authors: Sara Ghazanfari, Alexandre Araujo, Prashanth Krishnamurthy, Siddharth Garg, Farshad Khorrami
conference: "Arxiv"
year: 2024
bibkey: ghazanfari2024efficient
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.02080'}
  - {name: "Code", url: 'https://github.com/SaraGhazanfari/EMMA'}
tags: ['Has Code', 'Interpretability and Explainability', 'RAG', 'Security', 'Training Techniques', 'Merging', 'Multimodal Models', 'Reinforcement Learning']
---
Multi-modal Large Language Models (MLLMs) have recently exhibited impressive
general-purpose capabilities by leveraging vision foundation models to encode
the core concepts of images into representations. These are then combined with
instructions and processed by the language model to generate high-quality
responses. Despite significant progress in enhancing the language component,
challenges persist in optimally fusing visual encodings within the language
model for task-specific adaptability. Recent research has focused on improving
this fusion through modality adaptation modules but at the cost of
significantly increased model complexity and training data needs. In this
paper, we propose EMMA (Efficient Multi-Modal Adaptation), a lightweight
cross-modality module designed to efficiently fuse visual and textual
encodings, generating instruction-aware visual representations for the language
model. Our key contributions include: (1) an efficient early fusion mechanism
that integrates vision and language representations with minimal added
parameters (less than 0.2% increase in model size), (2) an in-depth
interpretability analysis that sheds light on the internal mechanisms of the
proposed method; (3) comprehensive experiments that demonstrate notable
improvements on both specialized and general benchmarks for MLLMs. Empirical
results show that EMMA boosts performance across multiple tasks by up to 9.3%
while significantly improving robustness against hallucinations. Our code is
available at https://github.com/SaraGhazanfari/EMMA
