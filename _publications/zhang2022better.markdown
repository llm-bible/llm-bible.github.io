---
layout: publication
title: 'Better Pre-training By Reducing Representation Confusion'
authors: Zhang Haojie, Liang Mingfei, Xie Ruobing, Sun Zhenlong, Zhang Bo, Lin Leyu
conference: "Arxiv"
year: 2022
bibkey: zhang2022better
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.04246"}
tags: ['Attention Mechanism', 'BERT', 'Efficiency And Optimization', 'Language Modeling', 'Masked Language Model', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
'In this work, we revisit the Transformer-based pre-trained language models and identify two different types of information confusion in position encoding and model representations, respectively. Firstly, we show that in the relative position encoding, the joint modeling about relative distances and directions brings confusion between two heterogeneous information. It may make the model unable to capture the associative semantics of the same distance and the opposite directions, which in turn affects the performance of downstream tasks. Secondly, we notice the BERT with Mask Language Modeling (MLM) pre-training objective outputs similar token representations (last hidden states of different tokens) and head representations (attention weights of different heads), which may make the diversity of information expressed by different tokens and heads limited. Motivated by the above investigation, we propose two novel techniques to improve pre-trained language models: Decoupled Directional Relative Position (DDRP) encoding and MTH pre-training objective. DDRP decouples the relative distance features and the directional features in classical relative position encoding. MTH applies two novel auxiliary regularizers besides MLM to enlarge the dissimilarities between (a) last hidden states of different tokens, and (b) attention weights of different heads. These designs allow the model to capture different categories of information more clearly, as a way to alleviate information confusion in representation learning for better optimization. Extensive experiments and ablation studies on GLUE benchmark demonstrate the effectiveness of our proposed methods.'
