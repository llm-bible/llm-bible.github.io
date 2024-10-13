---
layout: publication
title: 'Parameter-efficient Sparsity Crafting From Dense To Mixture-of-experts For Instruction Tuning On General Tasks'
authors: Wu Haoyuan, Zheng Haisheng, He Zhuolun, Yu Bei
conference: "Arxiv"
year: 2024
bibkey: wu2024parameter
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.02731"}
tags: ['GPT', 'Model Architecture', 'Uncategorized']
---
Large Language Models (LLMs) have demonstrated considerable proficiency in
general natural language processing (NLP) tasks. Instruction tuning, a
successful paradigm, enhances the ability of LLMs to follow natural language
instructions and exhibit robust generalization across a wide range of tasks.
However, these models often encounter performance limitations across multiple
tasks due to constrained model capacity. Expanding this capacity during the
instruction tuning phase poses significant challenges. To address this issue,
we introduce a novel approach, Parameter-Efficient Sparsity Crafting (PESC),
which transitions dense models to sparse models using a Mixture of Experts
(MoE) architecture. PESC integrates adapters into the MoE layers of sparse
models, differentiating experts without altering the individual weights within
these layers. This method significantly reduces computational costs and GPU
memory requirements, facilitating model capacity expansion through a minimal
increase in parameters via the inserted adapters. Our empirical evaluation
demonstrates the effectiveness of the PESC method. Using PESC during
instruction tuning, our sparse models, dubbed Camelidae outperform all other
opensource sparse models and exhibit superior general capabilities compared to
GPT3.5.
