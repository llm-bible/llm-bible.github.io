---
layout: publication
title: 'Bag Of Tricks For Effective Language Model Pretraining And Downstream Adaptation: A Case Study On GLUE'
authors: Qihuang Zhong, Liang Ding, Keqin Peng, Juhua Liu, Bo Du, Li Shen, Yibing Zhan, Dacheng Tao
conference: "Arxiv"
year: 2023
bibkey: zhong2023bag
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2302.09268"}
tags: ['Fine-Tuning', 'Transformer', 'Applications', 'RAG', 'Model Architecture', 'Security', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
This technical report briefly describes our JDExplore d-team's submission
Vega v1 on the General Language Understanding Evaluation (GLUE) leaderboard,
where GLUE is a collection of nine natural language understanding tasks,
including question answering, linguistic acceptability, sentiment analysis,
text similarity, paraphrase detection, and natural language inference. [Method]
We investigate several effective strategies and choose their best combination
setting as the training recipes. As for model structure, we employ the vanilla
Transformer with disentangled attention as the basic block encoder. For
self-supervised training, we employ the representative denoising objective
(i.e., replaced token detection) in phase 1 and combine the contrastive
objective (i.e., sentence embedding contrastive learning) with it in phase 2.
During fine-tuning, several advanced techniques such as transductive
fine-tuning, self-calibrated fine-tuning, and adversarial fine-tuning are
adopted. [Results] According to our submission record (Jan. 2022), with our
optimized pretraining and fine-tuning strategies, our 1.3 billion model sets
new state-of-the-art on 4/9 tasks, achieving the best average score of 91.3.
Encouragingly, our Vega v1 is the first to exceed powerful human performance on
the two challenging tasks, i.e., SST-2 and WNLI. We believe our empirically
successful recipe with a bag of tricks could shed new light on developing
efficient discriminative large language models.
