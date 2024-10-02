---
layout: publication
title: 'Promoting Generalized Cross-lingual Question Answering In Few-resource Scenarios Via Self-knowledge Distillation'
authors: Carrino Casimiro Pio, Escolano Carlos, Fonollosa José A. R.
conference: "Arxiv"
year: 2023
bibkey: carrino2023promoting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.17134"}
tags: ['Applications', 'Attention Mechanism', 'Distillation', 'Efficiency And Optimization', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
'Despite substantial progress in multilingual extractive Question Answering (QA), models with high and uniformly distributed performance across languages remain challenging, especially for languages with limited resources. We study cross-lingual transfer mainly focusing on the Generalized Cross-Lingual Transfer (G-XLT) task, where the question language differs from the context language - a challenge that has received limited attention thus far. Our approach seeks to enhance cross-lingual QA transfer using a high-performing multilingual model trained on a large-scale dataset, complemented by a few thousand aligned QA examples across languages. Our proposed strategy combines cross-lingual sampling and advanced self-distillation training in generations to tackle the previous challenge. Notably, we introduce the novel mAP@k coefficients to fine-tune self-knowledge distillation loss, dynamically regulating the teacher''s model knowledge to perform a balanced and effective knowledge transfer. We extensively evaluate our approach to assess XLT and G-XLT capabilities in extractive QA. Results reveal that our self-knowledge distillation approach outperforms standard cross-entropy fine-tuning by a significant margin. Importantly, when compared to a strong baseline that leverages a sizeable volume of machine-translated data, our approach shows competitive results despite the considerable challenge of operating within resource-constrained settings, even in zero-shot scenarios. Beyond performance improvements, we offer valuable insights through comprehensive analyses and an ablation study, further substantiating the benefits and constraints of our approach. In essence, we propose a practical solution to improve cross-lingual QA transfer by leveraging a few data resources in an efficient way.'
