---
layout: publication
title: FIRST Teach A Reliable Large Language Model Through Efficient Trustworthy Distillation
authors: Shum Kashun, Xu Minrui, Zhang Jianshu, Chen Zixin, Diao Shizhe, Dong Hanze, Zhang Jipeng, Raza Muhammad Omer
conference: "Arxiv"
year: 2024
bibkey: shum2024teach
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.12168"}
tags: ['Distillation', 'Efficiency And Optimization', 'RAG']
---
Large language models (LLMs) have become increasingly prevalent in our daily lives leading to an expectation for LLMs to be trustworthy 45;45; 45; both accurate and well45;calibrated (the prediction confidence should align with its ground truth correctness likelihood). Nowadays fine45;tuning has become the most popular method for adapting a model to practical usage by significantly increasing accuracy on downstream tasks. Despite the great accuracy it achieves we found fine45;tuning is still far away from satisfactory trustworthiness due to tuning45;induced mis45;calibration. In this paper we delve deeply into why and how mis45;calibration exists in fine45;tuned models and how distillation can alleviate the issue. Then we further propose a brand new method named Efficient Trustworthy Distillation (FIRST) which utilizes a small portion of teachers knowledge to obtain a reliable language model in a cost45;efficient way. Specifically we identify the concentrated knowledge phenomenon during distillation which can significantly reduce the computational burden. Then we apply a trustworthy maximization process to optimize the utilization of this small portion of concentrated knowledge before transferring it to the student. Experimental results demonstrate the effectiveness of our method where better accuracy (+2.337;) and less mis45;calibration (45;1037;) are achieved on average across both in45;domain and out45;of45;domain scenarios indicating better trustworthiness.
