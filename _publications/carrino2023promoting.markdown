---
layout: publication
title: Promoting Generalized Cross45;lingual Question Answering In Few45;resource Scenarios Via Self45;knowledge Distillation
authors: Carrino Casimiro Pio, Escolano Carlos, Fonollosa José A. R.
conference: "Arxiv"
year: 2023
bibkey: carrino2023promoting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.17134"}
tags: ['Applications', 'Attention Mechanism', 'Distillation', 'Efficiency And Optimization', 'Model Architecture', 'RAG', 'Training Techniques']
---
Despite substantial progress in multilingual extractive Question Answering (QA) models with high and uniformly distributed performance across languages remain challenging especially for languages with limited resources. We study cross45;lingual transfer mainly focusing on the Generalized Cross45;Lingual Transfer (G45;XLT) task where the question language differs from the context language 45; a challenge that has received limited attention thus far. Our approach seeks to enhance cross45;lingual QA transfer using a high45;performing multilingual model trained on a large45;scale dataset complemented by a few thousand aligned QA examples across languages. Our proposed strategy combines cross45;lingual sampling and advanced self45;distillation training in generations to tackle the previous challenge. Notably we introduce the novel mAP35;64;k coefficients to fine45;tune self45;knowledge distillation loss dynamically regulating the teachers model knowledge to perform a balanced and effective knowledge transfer. We extensively evaluate our approach to assess XLT and G45;XLT capabilities in extractive QA. Results reveal that our self45;knowledge distillation approach outperforms standard cross45;entropy fine45;tuning by a significant margin. Importantly when compared to a strong baseline that leverages a sizeable volume of machine45;translated data our approach shows competitive results despite the considerable challenge of operating within resource45;constrained settings even in zero45;shot scenarios. Beyond performance improvements we offer valuable insights through comprehensive analyses and an ablation study further substantiating the benefits and constraints of our approach. In essence we propose a practical solution to improve cross45;lingual QA transfer by leveraging a few data resources in an efficient way.
