---
layout: publication
title: Q-PEFT Query-dependent Parameter Efficient Fine-tuning For Text Reranking With Large Language Models
authors: Peng Zhiyuan, Wu Xuyang, Wang Qifan, Rajanala Sravanthi, Fang Yi
conference: "Arxiv"
year: 2024
bibkey: peng2024q
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.04522"}
tags: ['Attention Mechanism', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
Parameter Efficient Fine-Tuning (PEFT) methods have been extensively utilized in Large Language Models (LLMs) to improve the down-streaming tasks without the cost of fine-tuing the whole LLMs. Recent studies have shown how to effectively use PEFT for fine-tuning LLMs in ranking tasks with convincing performance; there are some limitations including the learned prompt being fixed for different documents overfitting to specific tasks and low adaptation ability. In this paper we introduce a query-dependent parameter efficient fine-tuning (Q-PEFT) approach for text reranking to leak the information of the true queries to LLMs and then make the generation of true queries from input documents much easier. Specifically we utilize the query to extract the top-k tokens from concatenated documents serving as contextual clues. We further augment Q-PEFT by substituting the retrieval mechanism with a multi-head attention layer to achieve end-to-end training and cover all the tokens in the documents guiding the LLMs to generate more document-specific synthetic queries thereby further improving the reranking performance. Extensive experiments are conducted on four public datasets demonstrating the effectiveness of our proposed approach.
