---
layout: publication
title: Deja Vu Contextual Sparsity For Efficient Llms At Inference Time
authors: Liu Zichang, Wang Jue, Dao Tri, Zhou Tianyi, Yuan Binhang, Song Zhao, Shrivastava Anshumali, Zhang Ce, Tian Yuandong, Re Christopher, Chen Beidi
conference: "Proceedings of the"
year: 2023
bibkey: liu2023deja
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.17157"}
  - {name: "Code", url: "https://github.com/FMInference/DejaVu"}
tags: ['Applications', 'Attention Mechanism', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Large language models (LLMs) with hundreds of billions of parameters have sparked a new wave of exciting AI applications. However they are computationally expensive at inference time. Sparsity is a natural approach to reduce this cost but existing methods either require costly retraining have to forgo LLMs in45;context learning ability or do not yield wall45;clock time speedup on modern hardware. We hypothesize that contextual sparsity which are small input45;dependent sets of attention heads and MLP parameters that yield approximately the same output as the dense model for a given input can address these issues. We show that contextual sparsity exists that it can be accurately predicted and that we can exploit it to speed up LLM inference in wall45;clock time without compromising LLMs quality or in45;context learning ability. Based on these insights we propose DejaVu a system that uses a low45;cost algorithm to predict contextual sparsity on the fly given inputs to each layer along with an asynchronous and hardware45;aware implementation that speeds up LLM inference. We validate that DejaVu can reduce the inference latency of OPT45;175B by over 2X compared to the state45;of45;the45;art FasterTransformer and over 6X compared to the widely used Hugging Face implementation without compromising model quality. The code is available at https://github.com/FMInference/DejaVu.
