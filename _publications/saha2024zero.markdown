---
layout: publication
title: On Zero-shot Counterspeech Generation By Llms
authors: Saha Punyajoy, Agrawal Aalok, Jana Abhik, Biemann Chris, Mukherjee Animesh
conference: "Arxiv"
year: 2024
bibkey: saha2024zero
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.14938"}
tags: ['Applications', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
With the emergence of numerous Large Language Models (LLM) the usage of such models in various Natural Language Processing (NLP) applications is increasing extensively. Counterspeech generation is one such key task where efforts are made to develop generative models by fine-tuning LLMs with hatespeech - counterspeech pairs but none of these attempts explores the intrinsic properties of large language models in zero-shot settings. In this work we present a comprehensive analysis of the performances of four LLMs namely GPT-2 DialoGPT ChatGPT and FlanT5 in zero-shot settings for counterspeech generation which is the first of its kind. For GPT-2 and DialoGPT we further investigate the deviation in performance with respect to the sizes (small medium large) of the models. On the other hand we propose three different prompting strategies for generating different types of counterspeech and analyse the impact of such strategies on the performance of the models. Our analysis shows that there is an improvement in generation quality for two datasets (1737;) however the toxicity increase (2537;) with increase in model size. Considering type of model GPT-2 and FlanT5 models are significantly better in terms of counterspeech quality but also have high toxicity as compared to DialoGPT. ChatGPT are much better at generating counter speech than other models across all metrics. In terms of prompting we find that our proposed strategies help in improving counter speech generation across all the models.
