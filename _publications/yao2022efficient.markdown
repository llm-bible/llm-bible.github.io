---
layout: publication
title: Zeroquant Efficient And Affordable Post45;training Quantization For Large45;scale Transformers
authors: Yao Zhewei, Aminabadi Reza Yazdani, Zhang Minjia, Wu Xiaoxia, Li Conglong, He Yuxiong
conference: "Arxiv"
year: 2022
bibkey: yao2022efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2206.01861"}
tags: ['Attention Mechanism', 'BERT', 'Distillation', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Quantization', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
How to efficiently serve ever45;larger trained natural language models in practice has become exceptionally challenging even for powerful cloud servers due to their prohibitive memory/computation requirements. In this work we present an efficient and affordable post45;training quantization approach to compress large Transformer45;based models termed as ZeroQuant. ZeroQuant is an end45;to45;end quantization and inference pipeline with three main components (1) a fine45;grained hardware45;friendly quantization scheme for both weight and activations; (2) a novel affordable layer45;by45;layer knowledge distillation algorithm (LKD) even without the access to the original training data; (3) a highly45;optimized quantization system backend support to remove the quantization/dequantization overhead. As such we are able to show that (1) ZeroQuant can reduce the precision for weights and activations to INT8 in a cost45;free way for both BERT and GPT345;style models with minimal accuracy impact which leads to up to 5.19x/4.16x speedup on those models compared to FP16 inference; (2) ZeroQuant plus LKD affordably quantize the weights in the fully45;connected module to INT4 along with INT8 weights in the attention module and INT8 activations resulting in 3x memory footprint reduction compared to the FP16 model; (3) ZeroQuant can be directly applied to two of the largest open45;sourced language models including GPT45;J6B and GPT45;NeoX20 for which our INT8 model achieves similar accuracy as the FP16 model but achieves up to 5.2x better efficiency.
