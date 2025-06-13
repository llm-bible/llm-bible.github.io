---
layout: publication
title: 'Math-perturb: Benchmarking Llms'' Math Reasoning Abilities Against Hard Perturbations'
authors: Kaixuan Huang, Jiacheng Guo, Zihao Li, Xiang Ji, Jiawei Ge, Wenzhe Li, Yingqing Guo, Tianle Cai, Hui Yuan, Runzhe Wang, Yue Wu, Ming Yin, Shange Tang, Yangsibo Huang, Chi Jin, Xinyun Chen, Chiyuan Zhang, Mengdi Wang
conference: "Arxiv"
year: 2025
bibkey: huang2025math
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.06453'}
tags: ['Reinforcement Learning', 'Prompting', 'In-Context Learning']
---
Large language models have demonstrated impressive performance on challenging
mathematical reasoning tasks, which has triggered the discussion of whether the
performance is achieved by true reasoning capability or memorization. To
investigate this question, prior work has constructed mathematical benchmarks
when questions undergo simple perturbations -- modifications that still
preserve the underlying reasoning patterns of the solutions. However, no work
has explored hard perturbations, which fundamentally change the nature of the
problem so that the original solution steps do not apply. To bridge the gap, we
construct MATH-P-Simple and MATH-P-Hard via simple perturbation and hard
perturbation, respectively. Each consists of 279 perturbed math problems
derived from level-5 (hardest) problems in the MATH dataset (Hendrycksmath et.
al., 2021). We observe significant performance drops on MATH-P-Hard across
various models, including o1-mini (-16.49%) and gemini-2.0-flash-thinking
(-12.9%). We also raise concerns about a novel form of memorization where
models blindly apply learned problem-solving skills without assessing their
applicability to modified contexts. This issue is amplified when using original
problems for in-context learning. We call for research efforts to address this
challenge, which is critical for developing more robust and reliable reasoning
models.
