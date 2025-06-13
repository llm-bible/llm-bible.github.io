---
layout: publication
title: 'Unlocking The Capabilities Of Vision-language Models For Generalizable And Explainable Deepfake Detection'
authors: Peipeng Yu, Jianwei Fei, Hui Gao, Xuan Feng, Zhihua Xia, Chip Hong Chang
conference: "Arxiv"
year: 2025
bibkey: yu2025unlocking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.14853'}
tags: ['Interpretability and Explainability', 'Tools', 'Prompting', 'Multimodal Models', 'Reinforcement Learning', 'Interpretability', 'Pretraining Methods']
---
Current vision-language models (VLMs) have demonstrated remarkable
capabilities in understanding multimodal data, but their potential remains
underexplored for deepfake detection due to the misaligned of their knowledge
and forensics patterns. To this end, we present a novel paradigm that unlocks
VLMs' potential capabilities through three components: (1) A knowledge-guided
forgery adaptation module that aligns VLM's semantic space with forensic
features through contrastive learning with external manipulation knowledge; (2)
A multi-modal prompt tuning framework that jointly optimizes visual-textual
embeddings for both localization and explainability; (3) An iterative
refinement strategy enabling multi-turn dialog for evidence-based reasoning.
Our framework includes a VLM-based Knowledge-guided Forgery Detector (KFD), a
VLM image encoder, and a Large Language Model (LLM). The VLM image encoder
extracts visual prompt embeddings from images, while the LLM receives visual
and question prompt embeddings for inference. The KFD is used to calculate
correlations between image features and pristine/deepfake class embeddings,
enabling forgery classification and localization. The outputs from these
components are used to construct forgery prompt embeddings. Finally, we feed
these prompt embeddings into the LLM to generate textual detection responses to
assist judgment. Extensive experiments on multiple benchmarks, including FF++,
CDF2, DFD, DFDCP, and DFDC, demonstrate that our scheme surpasses
state-of-the-art methods in generalization performance, while also supporting
multi-turn dialogue capabilities.
