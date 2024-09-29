---
layout: publication
title: Loqt Low45;rank Adapters For Quantized Pre45;training
authors: Loeschcke Sebastian, Toftrup Mads, Kastoryano Michael J., Belongie Serge, Snæbjarnarson Vésteinn
conference: "Arxiv"
year: 2024
bibkey: loeschcke2024low
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.16528"}
tags: ['Efficiency And Optimization', 'Language Modeling', 'Pretraining Methods', 'Quantization', 'Training Techniques']
---
Training of large neural networks requires significant computational resources. Despite advances using low45;rank adapters and quantization pretraining of models such as LLMs on consumer hardware has not been possible without model sharding offloading during training or per45;layer gradient updates. To address these limitations we propose LoQT a method for efficiently training quantized models. LoQT uses gradient45;based tensor factorization to initialize low45;rank trainable weight matrices that are periodically merged into quantized full45;rank weight matrices. Our approach is suitable for both pretraining and fine45;tuning of models which we demonstrate experimentally for language modeling and downstream task adaptation. We find that LoQT enables efficient training of models up to 7B parameters on a consumer45;grade 24GB GPU. We also demonstrate the feasibility of training a 13B parameter model using per45;layer gradient updates on the same hardware.
