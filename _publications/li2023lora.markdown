---
layout: publication
title: Loftq Lora45;fine45;tuning45;aware Quantization For Large Language Models
authors: Li Yixiao, Yu Yifan, Liang Chen, He Pengcheng, Karampatziakis Nikos, Chen Weizhu, Zhao Tuo
conference: "Arxiv"
year: 2023
bibkey: li2023lora
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.08659"}
  - {name: "Code", url: "https://github.com/yxli2123/LoftQ"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'Has Code', 'Quantization', 'Tools', 'Training Techniques']
---
Quantization is an indispensable technique for serving Large Language Models (LLMs) and has recently found its way into LoRA fine45;tuning. In this work we focus on the scenario where quantization and LoRA fine45;tuning are applied together on a pre45;trained model. In such cases it is common to observe a consistent gap in the performance on downstream tasks between full fine45;tuning and quantization plus LoRA fine45;tuning approach. In response we propose LoftQ (LoRA45;Fine45;Tuning45;aware Quantization) a novel quantization framework that simultaneously quantizes an LLM and finds a proper low45;rank initialization for LoRA fine45;tuning. Such an initialization alleviates the discrepancy between the quantized and full45;precision model and significantly improves generalization in downstream tasks. We evaluate our method on natural language understanding question answering summarization and natural language generation tasks. Experiments show that our method is highly effective and outperforms existing quantization methods especially in the challenging 245;bit and 2/445;bit mixed precision regimes. The code is available on https://github.com/yxli2123/LoftQ.
