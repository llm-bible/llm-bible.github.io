---
layout: publication
title: Black45;box Tuning For Language45;model45;as45;a45;service
authors: Sun Tianxiang, Shao Yunfan, Qian Hong, Huang Xuanjing, Qiu Xipeng
conference: "Arxiv"
year: 2022
bibkey: sun2022black
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2201.03514"}
tags: ['BERT', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Tools']
---
Extremely large pre45;trained language models (PTMs) such as GPT45;3 are usually released as a service. It allows users to design task45;specific prompts to query the PTMs through some black45;box APIs. In such a scenario which we call Language45;Model45;as45;a45;Service (LMaaS) the gradients of PTMs are usually unavailable. Can we optimize the task prompts by only accessing the model inference APIs This paper proposes the black45;box tuning framework to optimize the continuous prompt prepended to the input text via derivative45;free optimization. Instead of optimizing in the original high45;dimensional prompt space which is intractable for traditional derivative45;free optimization we perform optimization in a randomly generated subspace due to the low intrinsic dimensionality of large PTMs. The experimental results show that the black45;box tuning with RoBERTa on a few labeled samples not only significantly outperforms manual prompt and GPT45;3s in45;context learning but also surpasses the gradient45;based counterparts i.e. prompt tuning and full model tuning.
