---
layout: publication
title: Improving The Cross45;lingual Generalisation In Visual Question Answering
authors: Nooralahzadeh Farhad, Sennrich Rico
conference: "Arxiv"
year: 2022
bibkey: nooralahzadeh2022improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2209.02982"}
tags: ['Applications', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
While several benefits were realized for multilingual vision45;language pretrained models recent benchmarks across various tasks and languages showed poor cross45;lingual generalisation when multilingually pre45;trained vision45;language models are applied to non45;English data with a large gap between (supervised) English performance and (zero45;shot) cross45;lingual transfer. In this work we explore the poor performance of these models on a zero45;shot cross45;lingual visual question answering (VQA) task where models are fine45;tuned on English visual45;question data and evaluated on 7 typologically diverse languages. We improve cross45;lingual transfer with three strategies (1) we introduce a linguistic prior objective to augment the cross45;entropy loss with a similarity45;based loss to guide the model during training (2) we learn a task45;specific subnetwork that improves cross45;lingual generalisation and reduces variance without model modification (3) we augment training examples using synthetic code45;mixing to promote alignment of embeddings between source and target languages. Our experiments on xGQA using the pretrained multilingual multimodal transformers UC2 and M3P demonstrate the consistent effectiveness of the proposed fine45;tuning strategy for 7 languages outperforming existing transfer methods with sparse models. Code and data to reproduce our findings are publicly available.
