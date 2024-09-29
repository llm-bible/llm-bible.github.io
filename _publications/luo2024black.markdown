---
layout: publication
title: Crosstune Black45;box Few45;shot Classification With Label Enhancement
authors: Luo Danqing, Zhang Chen, Zhang Yan, Li Haizhou
conference: "Arxiv"
year: 2024
bibkey: luo2024black
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.12468"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Model Architecture', 'Prompting', 'RAG', 'Tools', 'Training Techniques']
---
Training or finetuning large45;scale language models (LLMs) requires substantial computation resources motivating recent efforts to explore parameter45;efficient adaptation to downstream tasks. One approach is to treat these models as black boxes and use forward passes (Inference APIs) to interact with them. Current research focuses on adapting these black45;box models to downstream tasks using gradient45;free prompt optimization but this often involves an expensive process of searching task45;specific prompts. Therefore we are motivated to study black45;box language model adaptation without prompt search. Specifically we introduce a label45;enhanced cross45;attention network called CrossTune which models the semantic relatedness between the input text sequence and task45;specific label descriptions. Its effectiveness is examined in the context of few45;shot text classification. To improve the generalization of CrossTune we utilize ChatGPT to generate additional training data through in45;context learning. A switch mechanism is implemented to exclude low45;quality ChatGPT45;generated data. Through extensive experiments on seven benchmark text classification datasets we demonstrate that our proposed approach outperforms the previous state45;of45;the45;art gradient45;free black45;box tuning method by 5.737; on average. Even without using ChatGPT45;augmented data CrossTune performs better or comparably than previous black45;box tuning methods suggesting the effectiveness of our approach.
