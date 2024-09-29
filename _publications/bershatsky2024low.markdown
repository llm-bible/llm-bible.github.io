---
layout: publication
title: 'Lotr: Low Tensor Rank Weight Adaptation'
authors: Bershatsky Daniel, Cherniuk Daria, Daulbaev Talgat, Mikhalev Aleksandr, Oseledets Ivan
conference: "Arxiv"
year: 2024
bibkey: bershatsky2024low
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.01376"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
In this paper we generalize and extend an idea of low-rank adaptation (LoRA) of large language models (LLMs) based on Transformer architecture. Widely used LoRA-like methods of fine-tuning LLMs are based on matrix factorization of gradient update. We introduce LoTR a novel approach for parameter-efficient fine-tuning of LLMs which represents a gradient update to parameters in a form of tensor decomposition. Low-rank adapter for each layer is constructed as a product of three matrices and tensor structure arises from sharing left and right multipliers of this product among layers. Simultaneous compression of a sequence of layers with low-rank tensor representation allows LoTR to archive even better parameter efficiency then LoRA especially for deep models. Moreover the core tensor does not depend on original weight dimension and can be made arbitrary small which allows for extremely cheap and fast downstream fine-tuning.
