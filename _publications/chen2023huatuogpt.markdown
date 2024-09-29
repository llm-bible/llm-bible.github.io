---
layout: publication
title: Huatuogpt-ii One-stage Training For Medical Adaption Of Llms
authors: Chen Junying, Wang Xidong, Gao Anningzhe, Jiang Feng, Chen Shunian, Zhang Hongbo, Song Dingjie, Xie Wenya, Kong Chuyi, Li Jianquan, Wan Xiang, Li Haizhou, Wang Benyou
conference: "Arxiv"
year: 2023
bibkey: chen2023huatuogpt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09774"}
tags: ['GPT', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning', 'Training Techniques']
---
Adapting a language model into a specific domain a.k.a domain adaption is a common practice when specialized knowledge e.g. medicine is not encapsulated in a general language model like Llama2. The challenge lies in the heterogeneity of data across the two training stages as it varies in languages genres or formats. To tackle this and simplify the learning protocol we propose to transform heterogeneous data from the both pre-training and supervised stages into a unified simple input-output pair format. We validate the new protocol in the domains where proprietary LLMs like ChatGPT perform relatively poorly such as Traditional Chinese Medicine. The developed model HuatuoGPT-II has shown state-of-the-art performance in Chinese medicine domain on a number of benchmarks e.g. medical licensing exams. It even outperforms proprietary models like ChatGPT and GPT-4 in some aspects especially in Traditional Chinese Medicine. Expert manual evaluations further validate HuatuoGPT-IIs advantages over existing LLMs. Notably HuatuoGPT-II was benchmarked in a fresh Chinese National Medical Licensing Examination where it achieved the best performance showcasing not only its effectiveness but also its generalization capabilities.
