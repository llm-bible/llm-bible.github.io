---
layout: publication
title: 'Empirical Evaluation Of Post-training Quantization Methods For Language Tasks'
authors: Hu Ting, Meinel Christoph, Yang Haojin
conference: "Arxiv"
year: 2022
bibkey: hu2022empirical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.16621"}
tags: ['BERT', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Quantization', 'Training Techniques', 'Transformer']
---
Transformer-based architectures like BERT have achieved great success in a wide range of Natural Language tasks. Despite their decent performance, the models still have numerous parameters and high computational complexity, impeding their deployment in resource-constrained environments. Post-Training Quantization (PTQ), which enables low-bit computations without extra training, could be a promising tool. In this work, we conduct an empirical evaluation of three PTQ methods on BERT-Base and BERT-Large: Linear Quantization (LQ), Analytical Clipping for Integer Quantization (ACIQ), and Outlier Channel Splitting (OCS). OCS theoretically surpasses the others in minimizing the Mean Square quantization Error and avoiding distorting the weights' outliers. That is consistent with the evaluation results of most language tasks of GLUE benchmark and a reading comprehension task, SQuAD. Moreover, low-bit quantized BERT models could outperform the corresponding 32-bit baselines on several small language tasks, which we attribute to the alleviation of over-parameterization. We further explore the limit of quantization bit and show that OCS could quantize BERT-Base and BERT-Large to 3-bits and retain 98&#37; and 96&#37; of the performance on the GLUE benchmark accordingly. Moreover, we conduct quantization on the whole BERT family, i.e., BERT models in different configurations, and comprehensively evaluate their performance on the GLUE benchmark and SQuAD, hoping to provide valuable guidelines for their deployment in various computation environments.
