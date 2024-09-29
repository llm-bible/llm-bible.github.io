---
layout: publication
title: Teaching Arithmetic To Small Transformers
authors: Lee Nayoung, Sreenivasan Kartik, Lee Jason D., Lee Kangwook, Papailiopoulos Dimitris
conference: "Arxiv"
year: 2023
bibkey: lee2023teaching
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.03381"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Tools', 'Training Techniques', 'Transformer']
---
Large language models like GPT45;4 exhibit emergent capabilities across general45;purpose tasks such as basic arithmetic when trained on extensive text data even though these tasks are not explicitly encoded by the unsupervised next45;token prediction objective. This study investigates how small transformers trained from random initialization can efficiently learn arithmetic operations such as addition multiplication and elementary functions like square root using the next45;token prediction objective. We first demonstrate that conventional training data is not the most effective for arithmetic learning and simple formatting changes can significantly improve accuracy. This leads to sharp phase transitions as a function of training data scale which in some cases can be explained through connections to low45;rank matrix completion. Building on prior work we then train on chain45;of45;thought style data that includes intermediate step results. Even in the complete absence of pretraining this approach significantly and simultaneously improves accuracy sample complexity and convergence speed. We also study the interplay between arithmetic and text data during training and examine the effects of few45;shot prompting pretraining and model scale. Additionally we discuss length generalization challenges. Our work highlights the importance of high45;quality instructive data that considers the particular characteristics of the next45;word prediction objective for rapidly eliciting arithmetic capabilities.
