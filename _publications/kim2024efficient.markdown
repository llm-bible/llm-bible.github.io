---
layout: publication
title: 'Efficient Generative Modeling With Residual Vector Quantization-based Tokens'
authors: Jaehyeon Kim, Taehong Moon, Keon Lee, Jaewoong Cho
conference: "Arxiv"
year: 2024
bibkey: kim2024efficient
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.10208'}
tags: ['Masked Language Model', 'Efficiency and Optimization', 'Tools', 'GPT', 'Quantization', 'Merging', 'Reinforcement Learning', 'Pretraining Methods']
---
We introduce ResGen, an efficient Residual Vector Quantization (RVQ)-based generative model for high-fidelity generation with fast sampling. RVQ improves data fidelity by increasing the number of quantization steps, referred to as depth, but deeper quantization typically increases inference steps in generative models. To address this, ResGen directly predicts the vector embedding of collective tokens rather than individual ones, ensuring that inference steps remain independent of RVQ depth. Additionally, we formulate token masking and multi-token prediction within a probabilistic framework using discrete diffusion and variational inference. We validate the efficacy and generalizability of the proposed method on two challenging tasks across different modalities: conditional image generation on ImageNet 256x256 and zero-shot text-to-speech synthesis. Experimental results demonstrate that ResGen outperforms autoregressive counterparts in both tasks, delivering superior performance without compromising sampling speed. Furthermore, as we scale the depth of RVQ, our generative models exhibit enhanced generation fidelity or faster sampling speeds compared to similarly sized baseline models.
