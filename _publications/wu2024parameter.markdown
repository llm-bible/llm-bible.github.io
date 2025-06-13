---
layout: publication
title: 'Parameter-efficient Sparsity Crafting From Dense To Mixture-of-experts For Instruction Tuning On General Tasks'
authors: Haoyuan Wu, Haisheng Zheng, Zhuolun He, Bei Yu
conference: "Arxiv"
year: 2024
bibkey: wu2024parameter
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.02731"}
  - {name: "Code", url: "https://github.com/wuhy68/Parameter-Efficient-MoE"}
tags: ['GPT', 'Has Code', 'Model Architecture']
---
Large language models (LLMs) have demonstrated considerable proficiency in
general natural language processing (NLP) tasks. Instruction tuning, a
successful paradigm, enhances the ability of LLMs to follow natural language
instructions and exhibit robust generalization across general tasks. However,
these models often encounter performance limitations across multiple tasks due
to constrained model capacity. Expanding this capacity during the instruction
tuning phase poses significant challenges. To address this issue, we introduce
parameter-efficient sparsity crafting (PESC), which crafts dense models into
sparse models using the mixture-of-experts (MoE) architecture. PESC integrates
adapters into the MoE layers of sparse models, differentiating experts without
altering the individual weights within these layers. This method significantly
reduces computational costs and GPU memory requirements, facilitating model
capacity expansion through a minimal parameter increase when guaranteeing the
quality of approximation in function space compared to original sparse
upcycling. Our empirical evaluation demonstrates the effectiveness of the PESC
method. Using PESC during instruction tuning, our best sparse model outperforms
other sparse and dense models and exhibits superior general capabilities
compared to GPT-3.5. Our code is available at
https://github.com/wuhy68/Parameter-Efficient-MoE.
