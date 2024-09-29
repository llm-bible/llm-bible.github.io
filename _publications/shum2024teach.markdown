---
layout: publication
title: FIRST: Teach A Reliable Large Language Model Through Efficient Trustworthy Distillation
authors: Shum Kashun, Xu Minrui, Zhang Jianshu, Chen Zixin, Diao Shizhe, Dong Hanze, Zhang Jipeng, Raza Muhammad Omer
conference: "Arxiv"
year: 2024
bibkey: shum2024teach
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.12168"}
tags: ['Distillation', 'Efficiency And Optimization', 'Fine Tuning', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Large language models (LLMs) have become increasingly prevalent in our daily lives leading to an expectation for LLMs to be trustworthy -- - both accurate and well-calibrated (the prediction confidence should align with its ground truth correctness likelihood). Nowadays fine-tuning has become the most popular method for adapting a model to practical usage by significantly increasing accuracy on downstream tasks. Despite the great accuracy it achieves we found fine-tuning is still far away from satisfactory trustworthiness due to tuning-induced mis-calibration. In this paper we delve deeply into why and how mis-calibration exists in fine-tuned models and how distillation can alleviate the issue. Then we further propose a brand new method named Efficient Trustworthy Distillation (FIRST) which utilizes a small portion of teachers knowledge to obtain a reliable language model in a cost-efficient way. Specifically we identify the concentrated knowledge phenomenon during distillation which can significantly reduce the computational burden. Then we apply a trustworthy maximization process to optimize the utilization of this small portion of concentrated knowledge before transferring it to the student. Experimental results demonstrate the effectiveness of our method where better accuracy (+2.337;) and less mis-calibration (-1037;) are achieved on average across both in-domain and out-of-domain scenarios indicating better trustworthiness.
