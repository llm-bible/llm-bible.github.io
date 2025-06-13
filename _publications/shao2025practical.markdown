---
layout: publication
title: 'POISONCRAFT: Practical Poisoning Of Retrieval-augmented Generation For Large Language Models'
authors: Yangguang Shao, Xinjie Lin, Haozheng Luo, Chengshang Hou, Gang Xiong, Jiahao Yu, Junzheng Shi
conference: "Arxiv"
year: 2025
bibkey: shao2025practical
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.06579'}
  - {name: "Code", url: 'https://github.com/AndyShaw01/PoisonCraft'}
tags: ['Has Code', 'RAG', 'Security', 'Applications', 'Reinforcement Learning']
---
Large language models (LLMs) have achieved remarkable success in various domains, primarily due to their strong capabilities in reasoning and generating human-like text. Despite their impressive performance, LLMs are susceptible to hallucinations, which can lead to incorrect or misleading outputs. This is primarily due to the lack of up-to-date knowledge or domain-specific information. Retrieval-augmented generation (RAG) is a promising approach to mitigate hallucinations by leveraging external knowledge sources. However, the security of RAG systems has not been thoroughly studied. In this paper, we study a poisoning attack on RAG systems named POISONCRAFT, which can mislead the model to refer to fraudulent websites. Compared to existing poisoning attacks on RAG systems, our attack is more practical as it does not require access to the target user query's info or edit the user query. It not only ensures that injected texts can be retrieved by the model, but also ensures that the LLM will be misled to refer to the injected texts in its response. We demonstrate the effectiveness of POISONCRAFTacross different datasets, retrievers, and language models in RAG pipelines, and show that it remains effective when transferred across retrievers, including black-box systems. Moreover, we present a case study revealing how the attack influences both the retrieval behavior and the step-by-step reasoning trace within the generation model, and further evaluate the robustness of POISONCRAFTunder multiple defense mechanisms. These results validate the practicality of our threat model and highlight a critical security risk for RAG systems deployed in real-world applications. We release our code\footnote\{https://github.com/AndyShaw01/PoisonCraft\} to support future research on the security and robustness of RAG systems in real-world settings.
