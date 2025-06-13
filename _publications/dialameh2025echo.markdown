---
layout: publication
title: 'Echo-llama: Efficient Caching For High-performance Llama Training'
authors: Maryam Dialameh, Rezaul Karim, Hossein Rajabzadeh, Omar Mohamed Awad, Hyock Ju Kwon, Boxing Chen, Walid Ahmed, Yang Liu
conference: "Arxiv"
year: 2025
bibkey: dialameh2025echo
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.17331"}
tags: ['Pretraining Methods', 'Training Techniques', 'Model Architecture']
---
This paper introduces ECHO-LLaMA, an efficient LLaMA architecture designed to improve both the training speed and inference throughput of LLaMA architectures while maintaining its learning capacity. ECHO-LLaMA transforms LLaMA models into shared KV caching across certain layers, significantly reducing KV computational complexity while maintaining or improving language performance. Experimental results demonstrate that ECHO-LLaMA achieves up to 77% higher token-per-second throughput during training, up to 16% higher Model FLOPs Utilization (MFU), and up to 14% lower loss when trained on an equal number of tokens. Furthermore, on the 1.1B model, ECHO-LLaMA delivers approximately 7% higher test-time throughput compared to the baseline. By introducing a computationally efficient adaptation mechanism, ECHO-LLaMA offers a scalable and cost-effective solution for pretraining and finetuning large language models, enabling faster and more resource-efficient training without compromising performance.
