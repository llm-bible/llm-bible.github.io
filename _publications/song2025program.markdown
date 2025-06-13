---
layout: publication
title: 'Progco: Program Helps Self-correction Of Large Language Models'
authors: Xiaoshuai Song, Yanan Wu, Weixun Wang, Jiaheng Liu, Wenbo Su, Bo Zheng
conference: "Arxiv"
year: 2025
bibkey: song2025program
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.01264'}
  - {name: "Code", url: 'https://github.com/songxiaoshuai/progco'}
tags: ['Has Code', 'Tools']
---
Self-Correction aims to enable large language models (LLMs) to self-verify and self-refine their initial responses without external feedback. However, LLMs often fail to effectively self-verify and generate correct feedback, further misleading refinement and leading to the failure of self-correction, especially in complex reasoning tasks. In this paper, we propose Program-driven Self-Correction (ProgCo). First, program-driven verification (ProgVe) achieves complex verification logic and extensive validation through self-generated, self-executing verification pseudo-programs. Then, program-driven refinement (ProgRe) receives feedback from ProgVe, conducts dual reflection and refinement on both responses and verification programs to mitigate misleading of incorrect feedback in complex reasoning tasks. Experiments on three instruction-following and mathematical benchmarks indicate that ProgCo achieves effective self-correction, and can be further enhance performance when combined with real program tools. We release our code at https://github.com/songxiaoshuai/progco.
