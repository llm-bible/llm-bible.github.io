---
layout: publication
title: Libra Building Decoupled Vision System on Large Language Models
authors: Xu Yifan, Yang Xiaoshan, Song Yaguang, Xu Changsheng
conference: "Arxiv"
year: 2024
bibkey: xu2024libra
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.10140"}
  - {name: "Code", url: "https://github.com/YifanXu74/Libra"}
tags: ['Attention Mechanism', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Training Techniques']
---
In this work we introduce Libra a prototype model with a decoupled vision system on a large language model (LLM). The decoupled vision system decouples inner-modal modeling and cross-modal interaction yielding unique visual information modeling and effective cross-modal comprehension. Libra is trained through discrete auto-regressive modeling on both vision and language inputs. Specifically we incorporate a routed visual expert with a cross-modal bridge module into a pretrained LLM to route the vision and language flows during attention computing to enable different attention patterns in inner-modal modeling and cross-modal interaction scenarios. Experimental results demonstrate that the dedicated design of Libra achieves a strong MLLM baseline that rivals existing works in the image-to-text scenario with merely 50 million training data providing a new perspective for future multimodal foundation models. Code is available at https://github.com/YifanXu74/Libra.
