---
layout: publication
title: Finequant: Unlocking Efficiency With Fine-grained Weight-only Quantization For Llms
authors: Kim Young Jin, Henry Rawn, Fahim Raffy, Awadalla Hany Hassan
conference: "Arxiv"
year: 2023
bibkey: kim2023unlocking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.09723"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Pretraining Methods', 'Quantization', 'Reinforcement Learning', 'Training Techniques']
---
Large Language Models (LLMs) have achieved state-of-the-art performance across various language tasks but pose challenges for practical deployment due to their substantial memory requirements. Furthermore the latest generative models suffer from high inference costs caused by the memory bandwidth bottleneck in the auto-regressive decoding process. To address these issues we propose an efficient weight-only quantization method that reduces memory consumption and accelerates inference for LLMs. To ensure minimal quality degradation we introduce a simple and effective heuristic approach that utilizes only the model weights of a pre-trained model. This approach is applicable to both Mixture-of-Experts (MoE) and dense models without requiring additional fine-tuning. To demonstrate the effectiveness of our proposed method we first analyze the challenges and issues associated with LLM quantization. Subsequently we present our heuristic approach which adaptively finds the granularity of quantization effectively addressing these problems. Furthermore we implement highly efficient GPU GEMMs that perform on-the-fly matrix multiplication and dequantization supporting the multiplication of fp16 or bf16 activations with int8 or int4 weights. We evaluate our approach on large-scale open source models such as OPT-175B and internal MoE models showcasing minimal accuracy loss while achieving up to 3.65 times higher throughput on the same number of GPUs.
