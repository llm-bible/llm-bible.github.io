---
layout: publication
title: LongLLMLingua Accelerating and Enhancing LLMs in Long Context Scenarios via Prompt Compression
authors: Jiang Huiqiang, Wu Qianhui, Luo Xufang, Li Dongsheng, Lin Chin-yew, Yang Yuqing, Qiu Lili
conference: "Arxiv"
year: 2023
bibkey: jiang2023longllmlingua
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.06839"}
  - {name: "Code", url: "https://aka.ms/LongLLMLingua"}
tags: ['ARXIV', 'Ethics And Bias', 'GPT', 'Has Code', 'Prompt']
---
In long context scenarios large language models (LLMs) face three main challenges higher computational cost performance reduction and position bias. Research indicates that LLM performance hinges on the density and position of key information in the input prompt. Inspired by these findings we propose LongLLMLingua for prompt compression towards improving LLMs perception of the key information to simultaneously address the three challenges. Our extensive evaluation across various long context scenarios demonstrates that LongLLMLingua not only enhances performance but also significantly reduces costs and latency. For instance in the NaturalQuestions benchmark LongLLMLingua boosts performance by up to 21.4 with around 4x fewer tokens in GPT-3.5-Turbo leading to substantial cost savings. It achieves a 94.0 cost reduction in the LooGLE benchmark. Moreover when compressing prompts of about 10k tokens at ratios of 2x-6x LongLLMLingua can accelerate end-to-end latency by 1.4x-2.6x. Our code is available at https://aka.ms/LongLLMLingua.
