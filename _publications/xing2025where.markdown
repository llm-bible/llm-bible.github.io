---
layout: publication
title: 'Where Do Large Vision-language Models Look At When Answering Questions?'
authors: Xiaoying Xing, Chia-wen Kuo, Li Fuxin, Yulei Niu, Fan Chen, Ming Li, Ying Wu, Longyin Wen, Sijie Zhu
conference: "Arxiv"
year: 2025
bibkey: xing2025where
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.13891"}
  - {name: "Code", url: "https://github.com/bytedance/LVLM_Interpretation"}
tags: ['Applications', 'Model Architecture', 'Reinforcement Learning', 'Attention Mechanism', 'Has Code', 'Multimodal Models']
---
Large Vision-Language Models (LVLMs) have shown promising performance in
vision-language understanding and reasoning tasks. However, their visual
understanding behaviors remain underexplored. A fundamental question arises: to
what extent do LVLMs rely on visual input, and which image regions contribute
to their responses? It is non-trivial to interpret the free-form generation of
LVLMs due to their complicated visual architecture (e.g., multiple encoders and
multi-resolution) and variable-length outputs. In this paper, we extend
existing heatmap visualization methods (e.g., iGOS++) to support LVLMs for
open-ended visual question answering. We propose a method to select visually
relevant tokens that reflect the relevance between generated answers and input
image. Furthermore, we conduct a comprehensive analysis of state-of-the-art
LVLMs on benchmarks designed to require visual information to answer. Our
findings offer several insights into LVLM behavior, including the relationship
between focus region and answer correctness, differences in visual attention
across architectures, and the impact of LLM scale on visual understanding. The
code and data are available at
https://github.com/bytedance/LVLM_Interpretation.
