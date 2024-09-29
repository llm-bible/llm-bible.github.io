---
layout: publication
title: Gemquad \: Generating Multilingual Question Answering Datasets From Large Language Models Using Few Shot Learning
authors: Namboori Amani, Mangale Shivam, Rosenbaum Andy, Soltan Saleh
conference: "Arxiv"
year: 2024
bibkey: namboori2024gemquad
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.09163"}
tags: ['Applications', 'Fine Tuning', 'In Context Learning', 'Pretraining Methods', 'Prompting', 'Tools', 'Training Techniques']
---
The emergence of Large Language Models (LLMs) with capabilities like In-Context Learning (ICL) has ushered in new possibilities for data generation across various domains while minimizing the need for extensive data collection and modeling techniques. Researchers have explored ways to use this generated synthetic data to optimize smaller student models for reduced deployment costs and lower latency in downstream tasks. However ICL-generated data often suffers from low quality as the task specificity is limited with few examples used in ICL. In this paper we propose GeMQuAD - a semi-supervised learning approach extending the WeakDAP framework applied to a dataset generated through ICL with just one example in the target language using AlexaTM 20B Seq2Seq LLM. Through our approach we iteratively identify high-quality data to enhance model performance especially for low-resource multilingual setting in the context of Extractive Question Answering task. Our framework outperforms the machine translation-augmented model by 0.22/1.68 F1/EM (Exact Match) points for Hindi and 0.82/1.37 F1/EM points for Spanish on the MLQA dataset and it surpasses the performance of model trained on an English-only dataset by 5.05/6.50 F1/EM points for Hindi and 3.81/3.69 points F1/EM for Spanish on the same dataset. Notably our approach uses a pre-trained LLM for generation with no fine-tuning (FT) utilizing just a single annotated example in ICL to generate data providing a cost-effective development process.
