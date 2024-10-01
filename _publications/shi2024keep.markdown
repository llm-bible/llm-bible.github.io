---
layout: publication
title: 'Keep The Cost Down: A Review On Methods To Optimize LLM'' S Kv-cache Consumption'
authors: Shi Luohe, Zhang Hongyi, Yao Yao, Li Zuchao, Zhao Hai
conference: "Arxiv"
year: 2024
bibkey: shi2024keep
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.18003"}
tags: ['Efficiency And Optimization', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Survey Paper', 'Training Techniques', 'Transformer']
---
Large Language Models (LLMs), epitomized by ChatGPT' s release in late 2022, have revolutionized various industries with their advanced language comprehension. However, their efficiency is challenged by the Transformer architecture' s struggle with handling long texts. KV-Cache has emerged as a pivotal solution to this issue, converting the time complexity of token generation from quadratic to linear, albeit with increased GPU memory overhead proportional to conversation length. With the development of the LLM community and academia, various KV-Cache compression methods have been proposed. In this review, we dissect the various properties of KV-Cache and elaborate on various methods currently used to optimize the KV-Cache space usage of LLMs. These methods span the pre-training phase, deployment phase, and inference phase, and we summarize the commonalities and differences among these methods. Additionally, we list some metrics for evaluating the long-text capabilities of large language models, from both efficiency and capability perspectives. Our review thus sheds light on the evolving landscape of LLM optimization, offering insights into future advancements in this dynamic field.
