---
layout: publication
title: Deja Vu&#58; Contextual Sparsity For Efficient Llms At Inference Time
authors: Liu Zichang, Wang Jue, Dao Tri, Zhou Tianyi, Yuan Binhang, Song Zhao, Shrivastava Anshumali, Zhang Ce, Tian Yuandong, Re Christopher, Chen Beidi
conference: "Proceedings of the"
year: 2023
bibkey: liu2023deja
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.17157"}
  - {name: "Code", url: "https://github.com/FMInference/DejaVu"}
tags: ['Applications', 'Attention Mechanism', 'Has Code', 'In Context Learning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques', 'Transformer']
---
Large language models (LLMs) with hundreds of billions of parameters have sparked a new wave of exciting AI applications. However they are computationally expensive at inference time. Sparsity is a natural approach to reduce this cost but existing methods either require costly retraining have to forgo LLMs in-context learning ability or do not yield wall-clock time speedup on modern hardware. We hypothesize that contextual sparsity which are small input-dependent sets of attention heads and MLP parameters that yield approximately the same output as the dense model for a given input can address these issues. We show that contextual sparsity exists that it can be accurately predicted and that we can exploit it to speed up LLM inference in wall-clock time without compromising LLMs quality or in-context learning ability. Based on these insights we propose DejaVu a system that uses a low-cost algorithm to predict contextual sparsity on the fly given inputs to each layer along with an asynchronous and hardware-aware implementation that speeds up LLM inference. We validate that DejaVu can reduce the inference latency of OPT-175B by over 2X compared to the state-of-the-art FasterTransformer and over 6X compared to the widely used Hugging Face implementation without compromising model quality. The code is available at https://github.com/FMInference/DejaVu."
