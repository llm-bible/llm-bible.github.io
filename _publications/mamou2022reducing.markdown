---
layout: publication
title: Tangobert&#58; Reducing Inference Cost By Using Cascaded Architecture
authors: Mamou Jonathan, Pereg Oren, Wasserblat Moshe, Schwartz Roy
conference: "Arxiv"
year: 2022
bibkey: mamou2022reducing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2204.06271"}
tags: ['BERT', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Transformer']
---
The remarkable success of large transformer-based models such as BERT RoBERTa and XLNet in many NLP tasks comes with a large increase in monetary and environmental cost due to their high computational load and energy consumption. In order to reduce this computational load in inference time we present TangoBERT a cascaded model architecture in which instances are first processed by an efficient but less accurate first tier model and only part of those instances are additionally processed by a less efficient but more accurate second tier model. The decision of whether to apply the second tier model is based on a confidence score produced by the first tier model. Our simple method has several appealing practical advantages compared to standard cascading approaches based on multi-layered transformer models. First it enables higher speedup gains (average lower latency). Second it takes advantage of batch size optimization for cascading which increases the relative inference cost reductions. We report TangoBERT inference CPU speedup on four text classification GLUE tasks and on one reading comprehension task. Experimental results show that TangoBERT outperforms efficient early exit baseline models; on the the SST-2 task it achieves an accuracy of 93.937; with a CPU speedup of 8.2x.
