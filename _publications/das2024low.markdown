---
layout: publication
title: Low45;rank Finetuning For Llms A Fairness Perspective
authors: Das Saswat, Romanelli Marco, Tran Cuong, Reza Zarreen, Kailkhura Bhavya, Fioretto Ferdinando
conference: "Arxiv"
year: 2024
bibkey: das2024low
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.18572"}
tags: ['Bias Mitigation', 'Ethics And Bias', 'Fairness']
---
Low45;rank approximation techniques have become the de facto standard for fine45;tuning Large Language Models (LLMs) due to their reduced computational and memory requirements. This paper investigates the effectiveness of these methods in capturing the shift of fine45;tuning datasets from the initial pre45;trained data distribution. Our findings reveal that there are cases in which low45;rank fine45;tuning falls short in learning such shifts. This in turn produces non45;negligible side effects especially when fine45;tuning is adopted for toxicity mitigation in pre45;trained models or in scenarios where it is important to provide fair models. Through comprehensive empirical evidence on several models datasets and tasks we show that low45;rank fine45;tuning inadvertently preserves undesirable biases and toxic behaviors. We also show that this extends to sequential decision45;making tasks emphasizing the need for careful evaluation to promote responsible LLMs development.
