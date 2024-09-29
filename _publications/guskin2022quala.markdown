---
layout: publication
title: Quala-minilm A Quantized Length Adaptive Minilm
authors: Guskin Shira, Wasserblat Moshe, Wang Chang, Shen Haihao
conference: "Arxiv"
year: 2022
bibkey: guskin2022quala
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.17114"}
tags: ['Applications', 'BERT', 'Distillation', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Quantization', 'Transformer']
---
Limited computational budgets often prevent transformers from being used in production and from having their high accuracy utilized. A knowledge distillation approach addresses the computational efficiency by self-distilling BERT into a smaller transformer representation having fewer layers and smaller internal embedding. However the performance of these models drops as we reduce the number of layers notably in advanced NLP tasks such as span question answering. In addition a separate model must be trained for each inference scenario with its distinct computational budget. Dynamic-TinyBERT tackles both limitations by partially implementing the Length Adaptive Transformer (LAT) technique onto TinyBERT achieving x3 speedup over BERT-base with minimal accuracy loss. In this work we expand the Dynamic-TinyBERT approach to generate a much more highly efficient model. We use MiniLM distillation jointly with the LAT method and we further enhance the efficiency by applying low-bit quantization. Our quantized length-adaptive MiniLM model (QuaLA-MiniLM) is trained only once dynamically fits any inference scenario and achieves an accuracy-efficiency trade-off superior to any other efficient approaches per any computational budget on the SQuAD1.1 dataset (up to x8.8 speedup with <137; accuracy loss). The code to reproduce this work is publicly available on Github.
