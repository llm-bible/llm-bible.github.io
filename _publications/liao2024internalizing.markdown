---
layout: publication
title: '\(\textit{skintern}\): Internalizing Symbolic Knowledge For Distilling Better Cot Capabilities Into Small Language Models'
authors: Huanxuan Liao, Shizhu He, Yupu Hao, Xiang Li, Yuanzhe Zhang, Jun Zhao, Kang Liu
conference: "Arxiv"
year: 2024
bibkey: liao2024internalizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.13183"}
  - {name: "Code", url: "https://github.com/Xnhyacinth/SKIntern"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Few-Shot', 'Reinforcement Learning', 'Distillation', 'Pretraining Methods', 'Fine-Tuning', 'Has Code', 'Attention Mechanism']
---
Small Language Models (SLMs) are attracting attention due to the high
computational demands and privacy concerns of Large Language Models (LLMs).
Some studies fine-tune SLMs using Chains of Thought (CoT) data distilled from
LLMs, aiming to enhance their reasoning ability. Furthermore, Some CoT
distillation methods introduce external symbolic knowledge into the generation
process to improve the limited knowledge memory, reasoning ability and
out-of-domain (OOD) generalization of SLMs. However, the introduction of
symbolic knowledge increases computational overhead and introduces potential
noise. In this paper, we introduce \\(\textit\{SKIntern\}\\), an innovative approach
that empowers SLMs to internalize symbolic knowledge and few-shot examples
gradually through a progressive fine-tuning process, guided by a predefined
linear decay schedule under curriculum learning. By efficiently internalizing
knowledge, \\(\textit\{SKIntern\}\\) reduces computational overhead and speeds up the
reasoning process by focusing solely on the question during inference. It
outperforms state-of-the-art baselines by over 5%, while reducing inference
costs (measured in FLOPs) by up to \\(4\times\\) across a wide range of SLMs in
both in-domain (ID) and out-of-domain (OOD) tasks. Our code will be available
at \url\{https://github.com/Xnhyacinth/SKIntern\}.
