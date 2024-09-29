---
layout: publication
title: Scaling Laws For Downstream Task Performance Of Large Language Models
authors: Isik Berivan, Ponomareva Natalia, Hazimeh Hussein, Paparas Dimitris, Vassilvitskii Sergei, Koyejo Sanmi
conference: "Arxiv"
year: 2024
bibkey: isik2024scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.04177"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'Large Scale Training', 'Model Architecture', 'Pretraining Methods', 'Scaling Laws', 'Training Techniques']
---
Scaling laws provide important insights that can guide the design of large language models (LLMs). Existing work has primarily focused on studying scaling laws for pretraining (upstream) loss. However in transfer learning settings in which LLMs are pretrained on an unsupervised dataset and then finetuned on a downstream task we often also care about the downstream performance. In this work we study the scaling behavior in a transfer learning setting where LLMs are finetuned for machine translation tasks. Specifically we investigate how the choice of the pretraining data and its size affect downstream performance (translation quality) as judged by two metrics downstream cross45;entropy and BLEU score. Our experiments indicate that the size of the finetuning dataset and the distribution alignment between the pretraining and downstream data significantly influence the scaling behavior. With sufficient alignment both downstream cross45;entropy and BLEU score improve monotonically with more pretraining data. In such cases we show that it is possible to predict the downstream BLEU score with good accuracy using a log45;law. However there are also cases where moderate misalignment causes the BLEU score to fluctuate or get worse with more pretraining whereas downstream cross45;entropy monotonically improves. By analyzing these observations we provide new practical insights for choosing appropriate pretraining data.
