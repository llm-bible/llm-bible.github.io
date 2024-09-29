---
layout: publication
title: Llmlingua Compressing Prompts For Accelerated Inference Of Large Language Models
authors: Jiang Huiqiang, Wu Qianhui, Lin Chin-yew, Yang Yuqing, Qiu Lili
conference: "Arxiv"
year: 2023
bibkey: jiang2023compressing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.05736"}
  - {name: "Code", url: "https://aka.ms/LLMLingua"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Prompting']
---
Large language models (LLMs) have been applied in various applications due to their astonishing capabilities. With advancements in technologies such as chain45;of45;thought (CoT) prompting and in45;context learning (ICL) the prompts fed to LLMs are becoming increasingly lengthy even exceeding tens of thousands of tokens. To accelerate model inference and reduce cost this paper presents LLMLingua a coarse45;to45;fine prompt compression method that involves a budget controller to maintain semantic integrity under high compression ratios a token45;level iterative compression algorithm to better model the interdependence between compressed contents and an instruction tuning based method for distribution alignment between language models. We conduct experiments and analysis over four datasets from different scenarios i.e. GSM8K BBH ShareGPT and Arxiv45;March23; showing that the proposed approach yields state45;of45;the45;art performance and allows for up to 20x compression with little performance loss. Our code is available at https://aka.ms/LLMLingua.
