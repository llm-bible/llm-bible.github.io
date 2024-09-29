---
layout: publication
title: Mitigating Hallucination In Visual Language Models With Visual Supervision
authors: Zhiyang Chen, Yousong Zhu, Yufei Zhan, Zhaowen Li, Chaoyang Zhao, Jinqiao Wang, Ming Tang
conference: "Arxiv"
year: 2023
bibkey: chen2023mitigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2311.16479v1"}
tags: ['Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Large vision45;language models (LVLMs) suffer from hallucination a lot generating responses that apparently contradict to the image content occasionally. The key problem lies in its weak ability to comprehend detailed content in a multi45;modal context which can be mainly attributed to two factors in training data and loss function. The vision instruction dataset primarily focuses on global description and the auto45;regressive loss function favors text modeling rather than image understanding. In this paper we bring more detailed vision annotations and more discriminative vision models to facilitate the training of LVLMs so that they can generate more precise responses without encounter hallucination. On one hand we generate image45;text pairs with detailed relationship annotations in panoptic scene graph dataset (PSG). These conversations pay more attention on detailed facts in the image encouraging the model to answer questions based on multi45;modal contexts. On the other hand we integrate SAM and mask prediction loss as auxiliary supervision forcing the LVLMs to have the capacity to identify context45;related objects so that they can generate more accurate responses mitigating hallucination. Moreover to provide a deeper evaluation on the hallucination in LVLMs we propose a new benchmark RAH45;Bench. It divides vision hallucination into three different types that contradicts the image with wrong categories attributes or relations and introduces False Positive Rate as detailed sub45;metric for each type. In this benchmark our approach demonstrates an +8.437; enhancement compared to original LLaVA and achieves widespread performance improvements across other models.
