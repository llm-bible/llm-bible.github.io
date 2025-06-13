---
layout: publication
title: 'OMCAT: Omni Context Aware Transformer'
authors: Arushi Goel, Karan Sapra, Matthieu Le, Rafael Valle, Andrew Tao, Bryan Catanzaro
conference: "Arxiv"
year: 2024
bibkey: goel2024omni
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.12109"}
  - {name: "Code", url: "https://om-cat.github.io"}
tags: ['Multimodal Models', 'Training Techniques', 'Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'Language Modeling', 'Pretraining Methods', 'Transformer', 'Has Code', 'Applications']
---
Large Language Models (LLMs) have made significant strides in text generation
and comprehension, with recent advancements extending into multimodal LLMs that
integrate visual and audio inputs. However, these models continue to struggle
with fine-grained, cross-modal temporal understanding, particularly when
correlating events across audio and video streams. We address these challenges
with two key contributions: a new dataset and model, called OCTAV and OMCAT
respectively. OCTAV (Omni Context and Temporal Audio Video) is a novel dataset
designed to capture event transitions across audio and video. Second, OMCAT
(Omni Context Aware Transformer) is a powerful model that leverages RoTE
(Rotary Time Embeddings), an innovative extension of RoPE, to enhance temporal
grounding and computational efficiency in time-anchored tasks. Through a robust
three-stage training pipeline-feature alignment, instruction tuning, and
OCTAV-specific training-OMCAT excels in cross-modal temporal understanding. Our
model demonstrates state-of-the-art performance on Audio-Visual Question
Answering (AVQA) tasks and the OCTAV benchmark, showcasing significant gains in
temporal reasoning and cross-modal alignment, as validated through
comprehensive experiments and ablation studies. Our dataset and code will be
made publicly available. The link to our demo page is https://om-cat.github.io.
