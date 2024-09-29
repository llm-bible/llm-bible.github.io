---
layout: publication
title: Pre45;training To Learn In Context
authors: Yuxian Gu, Li Dong, Furu Wei, Minlie Huang
conference: "Arxiv"
year: 2023
bibkey: gu2023pre
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2305.09137v1"}
  - {name: "Code", url: "https://github.com/thu&#45;coai/PICL"}
tags: ['Applications', 'Attention Mechanism', 'Has Code', 'Language Modeling', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
In45;context learning where pre45;trained language models learn to perform tasks from task examples and instructions in their contexts has attracted much attention in the NLP community. However the ability of in45;context learning is not fully exploited because language models are not explicitly trained to learn in context. To this end we propose PICL (Pre45;training for In45;Context Learning) a framework to enhance the language models in45;context learning ability by pre45;training the model on a large collection of intrinsic tasks in the general plain45;text corpus using the simple language modeling objective. PICL encourages the model to infer and perform tasks by conditioning on the contexts while maintaining task generalization of pre45;trained models. We evaluate the in45;context learning performance of the model trained with PICL on seven widely45;used text classification datasets and the Super45;NaturalInstrctions benchmark which contains 100+ NLP tasks formulated to text generation. Our experiments show that PICL is more effective and task45;generalizable than a range of baselines outperforming larger language models with nearly 4x parameters. The code is publicly available at https://github.com/thu&#45;coai/PICL.
