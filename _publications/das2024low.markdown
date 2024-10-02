---
layout: publication
title: 'Low-rank Finetuning For Llms: A Fairness Perspective'
authors: Das Saswat, Romanelli Marco, Tran Cuong, Reza Zarreen, Kailkhura Bhavya, Fioretto Ferdinando
conference: "Arxiv"
year: 2024
bibkey: das2024low
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.18572"}
tags: ['Bias Mitigation', 'Efficiency And Optimization', 'Ethics And Bias', 'Fairness', 'Fine Tuning', 'Pretraining Methods', 'Training Techniques']
---
Low-rank approximation techniques have become the de facto standard for fine-tuning Large Language Models (LLMs) due to their reduced computational and memory requirements. This paper investigates the effectiveness of these methods in capturing the shift of fine-tuning datasets from the initial pre-trained data distribution. Our findings reveal that there are cases in which low-rank fine-tuning falls short in learning such shifts. This, in turn, produces non-negligible side effects, especially when fine-tuning is adopted for toxicity mitigation in pre-trained models, or in scenarios where it is important to provide fair models. Through comprehensive empirical evidence on several models, datasets, and tasks, we show that low-rank fine-tuning inadvertently preserves undesirable biases and toxic behaviors. We also show that this extends to sequential decision-making tasks, emphasizing the need for careful evaluation to promote responsible LLMs development.
