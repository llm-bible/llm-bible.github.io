---
layout: publication
title: Quantization-aware And Tensor-compressed Training Of Transformers For Natural Language Understanding
authors: Yang Zi, Choudhary Samridhi, Kunzmann Siegfried, Zhang Zheng
conference: "Arxiv"
year: 2023
bibkey: yang2023quantization
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.01076"}
tags: ['Applications', 'Distillation', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Quantization', 'Training Techniques', 'Transformer']
---
Fine-tuned transformer models have shown superior performances in many natural language tasks. However the large model size prohibits deploying high-performance transformer models on resource-constrained devices. This paper proposes a quantization-aware tensor-compressed training approach to reduce the model size arithmetic operations and ultimately runtime latency of transformer-based models. We compress the embedding and linear layers of transformers into small low-rank tensor cores which significantly reduces model parameters. A quantization-aware training with learnable scale factors is used to further obtain low-precision representations of the tensor-compressed models. The developed approach can be used for both end-to-end training and distillation-based training. To improve the convergence a layer-by-layer distillation is applied to distill a quantized and tensor-compressed student model from a pre-trained transformer. The performance is demonstrated in two natural language understanding tasks showing up to 63(times) compression ratio little accuracy loss and remarkable inference and training speedup.
