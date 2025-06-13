---
layout: publication
title: 'Text-to-cad Generation Through Infusing Visual Feedback In Large Language Models'
authors: Ruiyu Wang, Yu Yuan, Shizhao Sun, Jiang Bian
conference: "Arxiv"
year: 2025
bibkey: wang2025text
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.19054'}
tags: ['Training Techniques', 'Tools', 'Merging', 'Multimodal Models', 'Reinforcement Learning']
---
Creating Computer-Aided Design (CAD) models requires significant expertise and effort. Text-to-CAD, which converts textual descriptions into CAD parametric sequences, is crucial in streamlining this process. Recent studies have utilized ground-truth parametric sequences, known as sequential signals, as supervision to achieve this goal. However, CAD models are inherently multimodal, comprising parametric sequences and corresponding rendered visual objects. Besides,the rendering process from parametric sequences to visual objects is many-to-one. Therefore, both sequential and visual signals are critical for effective training. In this work, we introduce CADFusion, a framework that uses Large Language Models (LLMs) as the backbone and alternates between two training stages: the sequential learning (SL) stage and the visual feedback (VF) stage. In the SL stage, we train LLMs using ground-truth parametric sequences, enabling the generation of logically coherent parametric sequences. In the VF stage, we reward parametric sequences that render into visually preferred objects and penalize those that do not, allowing LLMs to learn how rendered visual objects are perceived and evaluated. These two stages alternate throughout the training, ensuring balanced learning and preserving benefits of both signals. Experiments demonstrate that CADFusion significantly improves performance, both qualitatively and quantitatively.
