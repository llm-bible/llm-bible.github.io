---
layout: publication
title: Hidden In Plain Sight Exploring Chat History Tampering In Interactive Language Models
authors: Wei Cheng'an, Zhao Yue, Gong Yujia, Chen Kai, Xiang Lu, Zhu Shenchen
conference: "Arxiv"
year: 2024
bibkey: wei2024hidden
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.20234"}
tags: ['Applications', 'GPT', 'Language Modeling', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning']
---
Large Language Models (LLMs) such as ChatGPT and Llama have become prevalent in real45;world applications exhibiting impressive text generation performance. LLMs are fundamentally developed from a scenario where the input data remains static and unstructured. To behave interactively LLM45;based chat systems must integrate prior chat history as context into their inputs following a pre45;defined structure. However LLMs cannot separate user inputs from context enabling chat history tampering. This paper introduces a systematic methodology to inject user45;supplied history into LLM conversations without any prior knowledge of the target model. The key is to utilize prompt templates that can well organize the messages to be injected leading the target LLM to interpret them as genuine chat history. To automatically search for effective templates in a WebUI black45;box setting we propose the LLM45;Guided Genetic Algorithm (LLMGA) that leverages an LLM to generate and iteratively optimize the templates. We apply the proposed method to popular real45;world LLMs including ChatGPT and Llama45;2/3. The results show that chat history tampering can enhance the malleability of the models behavior over time and greatly influence the model output. For example it can improve the success rate of disallowed response elicitation up to 9737; on ChatGPT. Our findings provide insights into the challenges associated with the real45;world deployment of interactive LLMs.
