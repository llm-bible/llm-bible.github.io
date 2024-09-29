---
layout: publication
title: "Browse And Concentrate: Comprehending Multimodal Content Via Prior-llm Context Fusion"
authors: Wang Ziyue, Chen Chi, Zhu Yiqi, Luo Fuwen, Li Peng, Yan Ming, Zhang Ji, Huang Fei, Sun Maosong, Liu Yang
conference: "Arxiv"
year: 2024
bibkey: wang2024browse
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.12195"}
tags: ['Merging', 'Multimodal Models', 'RAG', 'Training Techniques']
---
With the bloom of Large Language Models (LLMs) Multimodal Large Language Models (MLLMs) that incorporate LLMs with pre-trained vision models have recently demonstrated impressive performance across diverse vision-language tasks. However they fall short to comprehend context involving multiple images. A primary reason for this shortcoming is that the visual features for each images are encoded individually by frozen encoders before feeding into the LLM backbone lacking awareness of other images and the multimodal instructions. We term this issue as prior-LLM modality isolation and propose a two phase paradigm browse-and-concentrate to enable in-depth multimodal context fusion prior to feeding the features into LLMs. This paradigm initially browses through the inputs for essential insights and then revisits the inputs to concentrate on crucial details guided by these insights to achieve a more comprehensive understanding of the multimodal inputs. Additionally we develop training strategies specifically to enhance the understanding of multi-image inputs. Our method markedly boosts the performance on 7 multi-image scenarios contributing to increments on average accuracy by 2.1337; and 7.6037; against strong MLLMs baselines with 3B and 11B LLMs respectively.
