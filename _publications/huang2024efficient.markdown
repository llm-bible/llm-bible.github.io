---
layout: publication
title: Mindmerger Efficient Boosting LLM Reasoning In Non45;english Languages
authors: Huang Zixian, Zhu Wenhao, Cheng Gong, Li Lei, Yuan Fei
conference: "Arxiv"
year: 2024
bibkey: huang2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.17386"}
tags: ['Applications', 'RAG', 'Training Techniques']
---
Reasoning capabilities are crucial for Large Language Models (LLMs) yet a notable gap exists between English and non45;English languages. To bridge this disparity some works fine45;tune LLMs to relearn reasoning capabilities in non45;English languages while others replace non45;English inputs with an external models outputs such as English translation text to circumvent the challenge of LLM understanding non45;English. Unfortunately these methods often underutilize the built45;in skilled reasoning and useful language understanding capabilities of LLMs. In order to better utilize the minds of reasoning and language understanding in LLMs we propose a new method namely MindMerger which merges LLMs with the external language understanding capabilities from multilingual models to boost the multilingual reasoning performance. Furthermore a two45;step training scheme is introduced to first train to embeded the external capabilities into LLMs and then train the collaborative utilization of the external capabilities and the built45;in capabilities in LLMs. Experiments on three multilingual reasoning datasets and a language understanding dataset demonstrate that MindMerger consistently outperforms all baselines especially in low45;resource languages. Without updating the parameters of LLMs the average accuracy improved by 6.737; and 8.037; across all languages and low45;resource languages on the MGSM dataset respectively.
