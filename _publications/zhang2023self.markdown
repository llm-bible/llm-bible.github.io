---
layout: publication
title: A Self45;enhancement Approach For Domain45;specific Chatbot Training Via Knowledge Mining And Digest
authors: Zhang Ruohong, Gao Luyu, Zheng Chen, Fan Zhen, Lai Guokun, Zhang Zheng, Ai Fangzhou, Yang Yiming, Yang Hongxia
conference: "Arxiv"
year: 2023
bibkey: zhang2023self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.10614"}
tags: ['Pretraining Methods', 'Training Techniques']
---
Large Language Models (LLMs) despite their great power in language generation often encounter challenges when dealing with intricate and knowledge45;demanding queries in specific domains. This paper introduces a novel approach to enhance LLMs by effectively extracting the relevant knowledge from domain45;specific textual sources and the adaptive training of a chatbot with domain45;specific inquiries. Our two45;step approach starts from training a knowledge miner namely LLMiner which autonomously extracts Question45;Answer pairs from relevant documents through a chain45;of45;thought reasoning process. Subsequently we blend the mined QA pairs with a conversational dataset to fine45;tune the LLM as a chatbot thereby enriching its domain45;specific expertise and conversational capabilities. We also developed a new evaluation benchmark which comprises four domain45;specific text corpora and associated human45;crafted QA pairs for testing. Our model shows remarkable performance improvement over generally aligned LLM and surpasses domain45;adapted models directly fine45;tuned on domain corpus. In particular LLMiner achieves this with minimal human intervention requiring only 600 seed instances thereby providing a pathway towards self45;improvement of LLMs through model45;synthesized training data.
