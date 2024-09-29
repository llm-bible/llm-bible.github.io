---
layout: publication
title: Llama45;adapter Efficient Fine45;tuning Of Language Models With Zero45;init Attention
authors: Zhang Renrui, Han Jiaming, Liu Chris, Gao Peng, Zhou Aojun, Hu Xiangfei, Yan Shilin, Lu Pan, Li Hongsheng, Qiao Yu
conference: "Arxiv"
year: 2023
bibkey: zhang2023llama
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.16199"}
  - {name: "Code", url: "https://github.com/OpenGVLab/LLaMA&#45;Adapter"}
tags: ['Attention Mechanism', 'BERT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques', 'Transformer']
---
We present LLaMA45;Adapter a lightweight adaption method to efficiently fine45;tune LLaMA into an instruction45;following model. Using 52K self45;instruct demonstrations LLaMA45;Adapter only introduces 1.2M learnable parameters upon the frozen LLaMA 7B model and costs less than one hour for fine45;tuning on 8 A100 GPUs. Specifically we adopt a set of learnable adaption prompts and prepend them to the word tokens at higher transformer layers. Then a zero45;initialized attention mechanism with zero gating is proposed which adaptively injects the new instructional cues into LLaMA while effectively preserves its pre45;trained knowledge. With our efficient training LLaMA45;Adapter can generate high45;quality responses comparable to Alpaca with fully fine45;tuned 7B parameters. Besides language commands our approach can be simply extended to multi45;modal instructions for learning image45;conditioned LLaMA model which achieves superior reasoning performance on ScienceQA and COCO Caption benchmarks. Furthermore we also evaluate the zero45;initialized attention mechanism for fine45;tuning other pre45;trained models (ViT RoBERTa) on traditional vision and language tasks demonstrating the superior generalization capacity of our approach. Code is released at https://github.com/OpenGVLab/LLaMA&#45;Adapter.
