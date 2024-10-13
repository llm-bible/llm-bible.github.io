---
layout: publication
title: 'Calrec: Contrastive Alignment Of Generative Llms For Sequential Recommendation'
authors: Li Yaoyiran, Zhai Xiang, Alzantot Moustafa, Yu Keyi, Vulić Ivan, Korhonen Anna, Hammad Mohamed
conference: "Arxiv"
year: 2024
bibkey: li2024contrastive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.02429"}
tags: ['Model Architecture', 'Pretraining Methods', 'Tools', 'Transformer']
---
Traditional recommender systems such as matrix factorization methods have
primarily focused on learning a shared dense embedding space to represent both
items and user preferences. Subsequently, sequence models such as RNN, GRUs,
and, recently, Transformers have emerged and excelled in the task of sequential
recommendation. This task requires understanding the sequential structure
present in users' historical interactions to predict the next item they may
like. Building upon the success of Large Language Models (LLMs) in a variety of
tasks, researchers have recently explored using LLMs that are pretrained on
vast corpora of text for sequential recommendation. To use LLMs for sequential
recommendation, both the history of user interactions and the model's
prediction of the next item are expressed in text form. We propose CALRec, a
two-stage LLM finetuning framework that finetunes a pretrained LLM in a
two-tower fashion using a mixture of two contrastive losses and a language
modeling loss: the LLM is first finetuned on a data mixture from multiple
domains followed by another round of target domain finetuning. Our model
significantly outperforms many state-of-the-art baselines (+37% in Recall@1 and
+24% in NDCG@10) and our systematic ablation studies reveal that (i) both
stages of finetuning are crucial, and, when combined, we achieve improved
performance, and (ii) contrastive alignment is effective among the target
domains explored in our experiments.
