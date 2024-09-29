---
layout: publication
title: Efficient And Effective Vocabulary Expansion Towards Multilingual Large Language Models
authors: Kim Seungduk, Choi Seungtaek, Jeong Myeongho
conference: "Arxiv"
year: 2024
bibkey: kim2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.14714"}
tags: ['Pretraining Methods', 'Training Techniques']
---
This report introduces a Korean adaptation of large language models that exhibit remarkable capabilities across English and Korean text understanding. Building on recent highly capable but English-centric LLMs such as SOLAR-10.7B and Phi-2 where non-English texts are inefficiently processed with English-centric tokenizers we present an efficient and effective vocabulary expansion (EEVE) method which encompasses parameter freezing and subword initialization. In contrast to previous efforts that believe new embeddings require trillions of training tokens we show that our method can significantly boost non-English proficiency within just 2 billion tokens. Surpassing most instruction-tuned LLMs on the Open Ko-LLM Leaderboard as of January 2024 our model ranks as the leading Korean pre-trained model in the open-source community according to Hugging Faces leaderboard. We open-source our models on Huggingface to empower the open research community in various languages.
