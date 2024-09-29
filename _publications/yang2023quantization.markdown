---
layout: publication
title: Quantization45;aware And Tensor45;compressed Training Of Transformers For Natural Language Understanding
authors: Yang Zi, Choudhary Samridhi, Kunzmann Siegfried, Zhang Zheng
conference: "Arxiv"
year: 2023
bibkey: yang2023quantization
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.01076"}
tags: ['Applications', 'Distillation', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Quantization', 'Training Techniques', 'Transformer']
---
Fine45;tuned transformer models have shown superior performances in many natural language tasks. However the large model size prohibits deploying high45;performance transformer models on resource45;constrained devices. This paper proposes a quantization45;aware tensor45;compressed training approach to reduce the model size arithmetic operations and ultimately runtime latency of transformer45;based models. We compress the embedding and linear layers of transformers into small low45;rank tensor cores which significantly reduces model parameters. A quantization45;aware training with learnable scale factors is used to further obtain low45;precision representations of the tensor45;compressed models. The developed approach can be used for both end45;to45;end training and distillation45;based training. To improve the convergence a layer45;by45;layer distillation is applied to distill a quantized and tensor45;compressed student model from a pre45;trained transformer. The performance is demonstrated in two natural language understanding tasks showing up to 63× compression ratio little accuracy loss and remarkable inference and training speedup.
