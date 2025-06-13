---
layout: publication
title: 'Hallucinate At The Last In Long Response Generation: A Case Study On Long Document Summarization'
authors: Joonho Yang, Seunghyun Yoon, Hwan Chang, Byeongjeong Kim, Hwanhee Lee
conference: "Arxiv"
year: 2025
bibkey: yang2025hallucinate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.15291"}
tags: ['Ethics and Bias', 'Applications', 'Language Modeling', 'Model Architecture', 'Reinforcement Learning', 'Attention Mechanism']
---
Large Language Models (LLMs) have significantly advanced text generation capabilities, including tasks like summarization, often producing coherent and fluent outputs. However, faithfulness to source material remains a significant challenge due to the generation of hallucinations. While extensive research focuses on detecting and reducing these inaccuracies, less attention has been paid to the positional distribution of hallucination within generated text, particularly in long outputs. In this work, we investigate where hallucinations occur in LLM-based long response generation, using long document summarization as a key case study. Focusing on the challenging setting of long context-aware long response generation, we find a consistent and concerning phenomenon: hallucinations tend to concentrate disproportionately in the latter parts of the generated long response. To understand this bias, we explore potential contributing factors related to the dynamics of attention and decoding over long sequences. Furthermore, we investigate methods to mitigate this positional hallucination, aiming to improve faithfulness specifically in the concluding segments of long outputs.
