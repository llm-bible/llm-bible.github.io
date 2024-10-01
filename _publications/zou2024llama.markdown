---
layout: publication
title: 'Llama-excitor: General Instruction Tuning Via Indirect Feature Interaction'
authors: Zou Bo, Yang Chao, Qiao Yu, Quan Chengbin, Zhao Youjian
conference: "Arxiv"
year: 2024
bibkey: zou2024llama
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.00913"}
tags: ['Attention Mechanism', 'Fine Tuning', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Prompting', 'Training Techniques', 'Transformer']
---
'Existing methods to fine-tune LLMs, like Adapter, Prefix-tuning, and LoRA, which introduce extra modules or additional input sequences to inject new skills or knowledge, may compromise the innate abilities of LLMs. In this paper, we propose LLaMA-Excitor, a lightweight method that stimulates the LLMs'' potential to better follow instructions by gradually paying more attention to worthwhile information. Specifically, the LLaMA-Excitor does not directly change the intermediate hidden state during the self-attention calculation of the transformer structure. We designed the Excitor block as a bypass module for the similarity score computation in LLMs'' self-attention to reconstruct keys and change the importance of values by learnable prompts. LLaMA-Excitor ensures a self-adaptive allocation of additional attention to input instructions, thus effectively preserving LLMs'' pre-trained knowledge when fine-tuning LLMs on low-quality instruction-following datasets. Furthermore, we unify the modeling of multi-modal tuning and language-only tuning, extending LLaMA-Excitor to a powerful visual instruction follower without the need for complex multi-modal alignment. Our proposed approach is evaluated in language-only and multi-modal tuning experimental scenarios. Notably, LLaMA-Excitor is the only method that maintains basic capabilities while achieving a significant improvement (+6&#37;) on the MMLU benchmark. In the visual instruction tuning, we achieve a new state-of-the-art image captioning performance of 157.5 CIDEr on MSCOCO, and a comparable performance (88.39&#37;) on ScienceQA to cutting-edge models with more parameters and extensive vision-language pertaining.'
