---
layout: publication
title: Contrans\: Weak-to-strong Alignment Engineering Via Concept Transplantation
authors: Dong Weilong, Wu Xinwei, Jin Renren, Xu Shaoyang, Xiong Deyi
conference: "Arxiv"
year: 2024
bibkey: dong2024weak
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.13578"}
tags: ['Pretraining Methods', 'Responsible AI', 'Tools', 'Training Techniques']
---
Ensuring large language models (LLM) behave consistently with human goals values and intentions is crucial for their safety but yet computationally expensive. To reduce the computational cost of alignment training of LLMs especially for those with a huge number of parameters and to reutilize learned value alignment we propose ConTrans a novel framework that enables weak-to-strong alignment transfer via concept transplantation. From the perspective of representation engineering ConTrans refines concept vectors in value alignment from a source LLM (usually a weak yet aligned LLM). The refined concept vectors are then reformulated to adapt to the target LLM (usually a strong yet unaligned base LLM) via affine transformation. In the third step ConTrans transplants the reformulated concept vectors into the residual stream of the target LLM. Experiments demonstrate the successful transplantation of a wide range of aligned concepts from 7B models to 13B and 70B models across multiple LLMs and LLM families. Remarkably ConTrans even surpasses instruction-tuned models in terms of truthfulness. Experiment results validate the effectiveness of both inter-LLM-family and intra-LLM-family concept transplantation. Our work successfully demonstrates an alternative way to achieve weak-to-strong alignment generalization and control.
