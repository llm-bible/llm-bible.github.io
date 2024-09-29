---
layout: publication
title: Maml-en-llm&#58; Model Agnostic Meta-training Of Llms For Improved In-context Learning
authors: Sinha Sanchit, Yue Yuguang, Soto Victor, Kulkarni Mayank, Lu Jianhua, Zhang Aidong
conference: "Arxiv"
year: 2024
bibkey: sinha2024maml
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.11446"}
tags: ['Fine Tuning', 'In Context Learning', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques']
---
Adapting large language models (LLMs) to unseen tasks with in-context training samples without fine-tuning remains an important research problem. To learn a robust LLM that adapts well to unseen tasks multiple meta-training approaches have been proposed such as MetaICL and MetaICT which involve meta-training pre-trained LLMs on a wide variety of diverse tasks. These meta-training approaches essentially perform in-context multi-task fine-tuning and evaluate on a disjointed test set of tasks. Even though they achieve impressive performance their goal is never to compute a truly general set of parameters. In this paper we propose MAML-en-LLM a novel method for meta-training LLMs which can learn truly generalizable parameters that not only perform well on disjointed tasks but also adapts to unseen tasks. We see an average increase of 237; on unseen domains in the performance while a massive 437; improvement on adaptation performance. Furthermore we demonstrate that MAML-en-LLM outperforms baselines in settings with limited amount of training data on both seen and unseen domains by an average of 237;. Finally we discuss the effects of type of tasks optimizers and task complexity an avenue barely explored in meta-training literature. Exhaustive experiments across 7 task settings along with two data settings demonstrate that models trained with MAML-en-LLM outperform SOTA meta-training approaches.
