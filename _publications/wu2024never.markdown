---
layout: publication
title: Never Miss A Beat&#58; An Efficient Recipe For Context Window Extension Of Large Language Models With Consistent "middle" Enhancement
authors: Wu Tong, Zhao Yanpeng, Zheng Zilong
conference: "Arxiv"
year: 2024
bibkey: wu2024never
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.07138"}
tags: ['Fine Tuning', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Recently many methods have been developed to extend the context length of pre-trained large language models (LLMs) but they often require fine-tuning at the target length ((gg)4K) and struggle to effectively utilize information from the middle part of the context. To address these issues we propose (textbfC)ontinuity-(textbfR)elativity ind(textbfE)xing with g(textbfA)ussian (textbfM)iddle (CREAM) which interpolates positional encodings by manipulating position indices. Apart from being simple CREAM is training-efficient it only requires fine-tuning at the pre-trained context window (eg Llama 2-4K) and can extend LLMs to a much longer target context length (eg 256K). To ensure that the model focuses more on the information in the middle we introduce a truncated Gaussian to encourage sampling from the middle part of the context during fine-tuning thus alleviating the Lost-in-the-Middle problem faced by long-context LLMs. Experimental results show that CREAM successfully extends LLMs to the target length for both Base and Chat versions of (texttt)Llama2-7B with Never Miss A Beat. Our code will be publicly available soon.
