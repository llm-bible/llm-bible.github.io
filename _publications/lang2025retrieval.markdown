---
layout: publication
title: 'Retrieval-augmented Dynamic Prompt Tuning For Incomplete Multimodal Learning'
authors: Jian Lang, Zhangtao Cheng, Ting Zhong, Fan Zhou
conference: "Arxiv"
year: 2025
bibkey: lang2025retrieval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.01120"}
  - {name: "Code", url: "https://github.com/Jian-Lang/RAGPT"}
tags: ['Transformer', 'Tools', 'GPT', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Security', 'Has Code', 'Pretraining Methods', 'Multimodal Models', 'Prompting']
---
Multimodal learning with incomplete modality is practical and challenging.
Recently, researchers have focused on enhancing the robustness of pre-trained
MultiModal Transformers (MMTs) under missing modality conditions by applying
learnable prompts. However, these prompt-based methods face several
limitations: (1) incomplete modalities provide restricted modal cues for
task-specific inference, (2) dummy imputation for missing content causes
information loss and introduces noise, and (3) static prompts are
instance-agnostic, offering limited knowledge for instances with various
missing conditions. To address these issues, we propose RAGPT, a novel
Retrieval-AuGmented dynamic Prompt Tuning framework. RAGPT comprises three
modules: (I) the multi-channel retriever, which identifies similar instances
through a within-modality retrieval strategy, (II) the missing modality
generator, which recovers missing information using retrieved contexts, and
(III) the context-aware prompter, which captures contextual knowledge from
relevant instances and generates dynamic prompts to largely enhance the MMT's
robustness. Extensive experiments conducted on three real-world datasets show
that RAGPT consistently outperforms all competitive baselines in handling
incomplete modality problems. The code of our work and prompt-based baselines
is available at https://github.com/Jian-Lang/RAGPT.
