---
layout: publication
title: 'Taking A Deep Breath: Enhancing Language Modeling Of Large Language Models With Sentinel Tokens'
authors: Luo Weiyao, Zheng Suncong, Xia Heming, Wang Weikang, Lei Yan, Liu Tianyu, Chen Shuang, Sui Zhifang
conference: "Arxiv"
year: 2024
bibkey: luo2024taking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.10985"}
tags: ['Attention Mechanism', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Tools', 'Transformer']
---
Large language models (LLMs) have shown promising efficacy across various tasks becoming powerful tools in numerous aspects of human life. However Transformer-based LLMs suffer a performance degradation when modeling long-term contexts due to they discard some information to reduce computational overhead. In this work we propose a simple yet effective method to enable LLMs to take a deep breath encouraging them to summarize information contained within discrete text chunks. Specifically we segment the text into multiple chunks and insert special token <SR at the end of each chunk. We then modify the attention mask to integrate the chunks information into the corresponding <SR token. This facilitates LLMs to interpret information not only from historical individual tokens but also from the <SR token aggregating the chunks semantic information. Experiments on language modeling and out-of-domain downstream tasks validate the superiority of our approach.
