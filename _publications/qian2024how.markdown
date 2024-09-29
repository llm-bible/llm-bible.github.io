---
layout: publication
title: How Easy Is It To Fool Your Multimodal Llms An Empirical Analysis On Deceptive Prompts
authors: Qian Yusu, Zhang Haotian, Yang Yinfei, Gan Zhe
conference: "Arxiv"
year: 2024
bibkey: qian2024how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.13220"}
tags: ['GPT', 'Model Architecture', 'Multimodal Models', 'Prompting', 'RAG', 'Reinforcement Learning', 'Security']
---
The remarkable advancements in Multimodal Large Language Models (MLLMs) have not rendered them immune to challenges particularly in the context of handling deceptive information in prompts thus producing hallucinated responses under such conditions. To quantitatively assess this vulnerability we present MAD45;Bench a carefully curated benchmark that contains 1000 test samples divided into 5 categories such as non45;existent objects count of objects and spatial relationship. We provide a comprehensive analysis of popular MLLMs ranging from GPT45;4v Reka Gemini45;Pro to open45;sourced models such as LLaVA45;NeXT and MiniCPM45;Llama3. Empirically we observe significant performance gaps between GPT45;4o and other models; and previous robust instruction45;tuned models are not effective on this new benchmark. While GPT45;4o achieves 82.8237; accuracy on MAD45;Bench the accuracy of any other model in our experiments ranges from 937; to 5037;. We further propose a remedy that adds an additional paragraph to the deceptive prompts to encourage models to think twice before answering the question. Surprisingly this simple method can even double the accuracy; however the absolute numbers are still too low to be satisfactory. We hope MAD45;Bench can serve as a valuable benchmark to stimulate further research to enhance model resilience against deceptive prompts.
