---
layout: publication
title: Understanding Linear Probing Then Fine45;tuning Language Models From NTK Perspective
authors: Tomihari Akiyoshi, Sato Issei
conference: "Arxiv"
year: 2024
bibkey: tomihari2024understanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.16747"}
  - {name: "Code", url: "https://github.com/tom4649/lp&#45;ft&#95;ntk"}
tags: ['Fine Tuning', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
The two45;stage fine45;tuning (FT) method linear probing then fine45;tuning (LP45;FT) consistently outperforms linear probing (LP) and FT alone in terms of accuracy for both in45;distribution (ID) and out45;of45;distribution (OOD) data. This success is largely attributed to the preservation of pre45;trained features achieved through a near45;optimal linear head obtained during LP. However despite the widespread use of large language models the exploration of complex architectures such as Transformers remains limited. In this paper we analyze the training dynamics of LP45;FT for classification models on the basis of the neural tangent kernel (NTK) theory. Our analysis decomposes the NTK matrix into two components highlighting the importance of the linear head norm alongside the prediction accuracy at the start of the FT stage. We also observe a significant increase in the linear head norm during LP stemming from training with the cross45;entropy (CE) loss which effectively minimizes feature changes. Furthermore we find that this increased norm can adversely affect model calibration a challenge that can be addressed by temperature scaling. Additionally we extend our analysis with the NTK to the low45;rank adaptation (LoRA) method and validate its effectiveness. Our experiments with a Transformer45;based model on natural language processing tasks across multiple benchmarks confirm our theoretical analysis and demonstrate the effectiveness of LP45;FT in fine45;tuning language models. Code is available at https://github.com/tom4649/lp&#45;ft&#95;ntk.
