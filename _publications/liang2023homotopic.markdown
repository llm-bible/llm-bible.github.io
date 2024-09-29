---
layout: publication
title: Homodistil Homotopic Task45;agnostic Distillation Of Pre45;trained Transformers
authors: Liang Chen, Jiang Haoming, Li Zheng, Tang Xianfeng, Yin Bin, Zhao Tuo
conference: "Arxiv"
year: 2023
bibkey: liang2023homotopic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2302.09632"}
tags: ['Distillation', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Pruning', 'Quantization', 'Training Techniques', 'Transformer']
---
Knowledge distillation has been shown to be a powerful model compression approach to facilitate the deployment of pre45;trained language models in practice. This paper focuses on task45;agnostic distillation. It produces a compact pre45;trained model that can be easily fine45;tuned on various tasks with small computational costs and memory footprints. Despite the practical benefits task45;agnostic distillation is challenging. Since the teacher model has a significantly larger capacity and stronger representation power than the student model it is very difficult for the student to produce predictions that match the teachers over a massive amount of open45;domain training data. Such a large prediction discrepancy often diminishes the benefits of knowledge distillation. To address this challenge we propose Homotopic Distillation (HomoDistil) a novel task45;agnostic distillation approach equipped with iterative pruning. Specifically we initialize the student model from the teacher model and iteratively prune the students neurons until the target width is reached. Such an approach maintains a small discrepancy between the teachers and students predictions throughout the distillation process which ensures the effectiveness of knowledge transfer. Extensive experiments demonstrate that HomoDistil achieves significant improvements on existing baselines.
