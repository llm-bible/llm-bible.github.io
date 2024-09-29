---
layout: publication
title: Never Miss A Beat An Efficient Recipe For Context Window Extension Of Large Language Models With Consistent middle Enhancement
authors: Wu Tong, Zhao Yanpeng, Zheng Zilong
conference: "Arxiv"
year: 2024
bibkey: wu2024never
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.07138"}
tags: ['Model Architecture', 'RAG', 'Training Techniques']
---
Recently many methods have been developed to extend the context length of pre45;trained large language models (LLMs) but they often require fine45;tuning at the target length (gg4K) and struggle to effectively utilize information from the middle part of the context. To address these issues we propose textbf123;C125;ontinuity45;textbf123;R125;elativity indtextbf123;E125;xing with gtextbf123;A125;ussian textbf123;M125;iddle (CREAM) which interpolates positional encodings by manipulating position indices. Apart from being simple CREAM is training45;efficient it only requires fine45;tuning at the pre45;trained context window (eg Llama 245;4K) and can extend LLMs to a much longer target context length (eg 256K). To ensure that the model focuses more on the information in the middle we introduce a truncated Gaussian to encourage sampling from the middle part of the context during fine45;tuning thus alleviating the Lost45;in45;the45;Middle problem faced by long45;context LLMs. Experimental results show that CREAM successfully extends LLMs to the target length for both Base and Chat versions of texttt123;Llama245;7B125; with Never Miss A Beat. Our code will be publicly available soon.
