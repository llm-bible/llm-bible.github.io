---
layout: publication
title: 'Tokenization Matters! Degrading Large Language Models Through Challenging Their Tokenization'
authors: Wang Dixuan, Li Yanda, Jiang Junyuan, Ding Zepeng, Jiang Guochao, Liang Jiaqing, Yang Deqing
conference: "Arxiv"
year: 2024
bibkey: wang2024tokenization
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.17067"}
tags: ['Ethics And Bias', 'GPT', 'Model Architecture', 'Security', 'Tokenization']
---
Large Language Models (LLMs) have shown remarkable capabilities in language understanding and generation. Nonetheless it was also witnessed that LLMs tend to produce inaccurate responses to specific queries. This deficiency can be traced to the tokenization step LLMs must undergo which is an inevitable limitation inherent to all LLMs. In fact incorrect tokenization is the critical point that hinders LLMs in understanding the input precisely thus leading to unsatisfactory output. To demonstrate this flaw of LLMs we construct an adversarial dataset named as textbfADT (Adversarial Dataset for Tokenizer) which draws upon the vocabularies of various open-source LLMs to challenge LLMs tokenization. ADT consists of two subsets the manually constructed ADT-Human and the automatically generated ADT-Auto. Our empirical results reveal that our ADT is highly effective on challenging the tokenization of leading LLMs including GPT-4o Llama-3 Qwen2.5-max and so on thus degrading these LLMs capabilities. Moreover our method of automatic data generation has been proven efficient and robust which can be applied to any open-source LLMs. To the best of our knowledge our study is the first to investigating LLMs vulnerability in terms of challenging their token segmentation which will shed light on the subsequent research of improving LLMs capabilities through optimizing their tokenization process and algorithms.
