---
layout: publication
title: Hypertuning Toward Adapting Large Language Models Without Back45;propagation
authors: Phang Jason, Mao Yi, He Pengcheng, Chen Weizhu
conference: "Arxiv"
year: 2022
bibkey: phang2022toward
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2211.12485"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'Language Modeling', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Fine45;tuning large language models for different tasks can be costly and inefficient and even methods that reduce the number of tuned parameters still require full gradient45;based optimization. We propose HyperTuning a novel approach to model adaptation that uses a hypermodel to generate task45;specific parameters for a fixed downstream model. We demonstrate a simple setup for hypertuning with HyperT5 a T545;based hypermodel that produces soft prefixes or LoRA parameters for a frozen T5 model from few45;shot examples. We train HyperT5 in two stages first hyperpretraining with a modified conditional language modeling objective that trains a hypermodel to generate parameters; second multi45;task fine45;tuning (MTF) on a large number of diverse language tasks. We evaluate HyperT5 on P3 MetaICL and Super45;NaturalInstructions datasets and show that it can effectively generate parameters for unseen tasks. Moreover we show that using hypermodel45;generated parameters as initializations for further parameter45;efficient fine45;tuning improves performance. HyperTuning can thus be a flexible and efficient way to leverage large language models for diverse downstream applications.
