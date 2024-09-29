---
layout: publication
title: 'Multimodal Multi-hop Question Answering Through A Conversation Between Tools And Efficiently Finetuned Large Language Models'
authors: Rajabzadeh Hossein, Wang Suyuchen, Kwon Hyock Ju, Liu Bang
conference: "Arxiv"
year: 2023
bibkey: rajabzadeh2023multimodal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.08922"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Multimodal Models', 'Prompting', 'Tools']
---
We employ a tool-interacting divide-and-conquer strategy enabling large language models (LLMs) to answer complex multimodal multi-hop questions. In particular we harness the power of large language models to divide a given multimodal multi-hop question into unimodal single-hop sub-questions to be answered by the appropriate tool from a predefined set of tools. After all corresponding tools provide the LLM with their answers the LLM generates the next relevant unimodal single-hop question. To increase the reasoning ability of LLMs we prompt chatGPT to generate a tool-interacting divide-and-conquer dataset. This dataset is then used to efficiently finetune the corresponding LLM. To assess the effectiveness of this approach we conduct an evaluation on two recently introduced complex question-answering datasets. The experimental analysis demonstrate substantial improvements over existing state-of-the-art solutions indicating the efficacy and generality of our strategy
