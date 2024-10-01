---
layout: publication
title: 'Model Compression With Two-stage Multi-teacher Knowledge Distillation For Web Question Answering System'
authors: Yang Ze, Shou Linjun, Gong Ming, Lin Wutao, Jiang Daxin
conference: "Arxiv"
year: 2019
bibkey: yang2019model
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1910.08381"}
tags: ['Applications', 'BERT', 'Distillation', 'Efficiency And Optimization', 'Ethics And Bias', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Quantization', 'Training Techniques']
---
"Deep pre-training and fine-tuning models (such as BERT and OpenAI GPT) have demonstrated excellent results in question answering areas. However, due to the sheer amount of model parameters, the inference speed of these models is very slow. How to apply these complex models to real business scenarios becomes a challenging but practical problem. Previous model compression methods usually suffer from information loss during the model compression procedure, leading to inferior models compared with the original one. To tackle this challenge, we propose a Two-stage Multi-teacher Knowledge Distillation (TMKD for short) method for web Question Answering system. We first develop a general Q\&amp;A distillation task for student model pre-training, and further fine-tune this pre-trained student model with multi-teacher knowledge distillation on downstream tasks (like Web Q\&amp;A task, MNLI, SNLI, RTE tasks from GLUE), which effectively reduces the overfitting bias in individual teacher models, and transfers more general knowledge to the student model. The experiment results show that our method can significantly outperform the baseline methods and even achieve comparable results with the original teacher models, along with substantial speedup of model inference."
