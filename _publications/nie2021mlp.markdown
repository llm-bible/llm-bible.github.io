---
layout: publication
title: MLP Architectures For Vision45;and45;language Modeling An Empirical Study
authors: Nie Yixin, Li Linjie, Gan Zhe, Wang Shuohang, Zhu Chenguang, Zeng Michael, Liu Zicheng, Bansal Mohit, Wang Lijuan
conference: "Arxiv"
year: 2021
bibkey: nie2021mlp
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2112.04453"}
  - {name: "Code", url: "https://github.com/easonnie/mlp&#45;vil"}
tags: ['Attention Mechanism', 'Ethics And Bias', 'Has Code', 'Language Modeling', 'Merging', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
We initiate the first empirical study on the use of MLP architectures for vision45;and45;language (VL) fusion. Through extensive experiments on 5 VL tasks and 5 robust VQA benchmarks we find that (i) Without pre45;training using MLPs for multimodal fusion has a noticeable performance gap compared to transformers; (ii) However VL pre45;training can help close the performance gap; (iii) Instead of heavy multi45;head attention adding tiny one45;head attention to MLPs is sufficient to achieve comparable performance to transformers. Moreover we also find that the performance gap between MLPs and transformers is not widened when being evaluated on the harder robust VQA benchmarks suggesting using MLPs for VL fusion can generalize roughly to a similar degree as using transformers. These results hint that MLPs can effectively learn to align vision and text features extracted from lower45;level encoders without heavy reliance on self45;attention. Based on this we ask an even bolder question can we have an all45;MLP architecture for VL modeling where both VL fusion and the vision encoder are replaced with MLPs Our result shows that an all45;MLP VL model is sub45;optimal compared to state45;of45;the45;art full45;featured VL models when both of them get pre45;trained. However pre45;training an all45;MLP can surprisingly achieve a better average score than full45;featured transformer models without pre45;training. This indicates the potential of large45;scale pre45;training of MLP45;like architectures for VL modeling and inspires the future research direction on simplifying well45;established VL modeling with less inductive design bias. Our code is publicly available at https://github.com/easonnie/mlp&#45;vil
