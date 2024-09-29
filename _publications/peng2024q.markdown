---
layout: publication
title: Q45;PEFT Query45;dependent Parameter Efficient Fine45;tuning For Text Reranking With Large Language Models
authors: Peng Zhiyuan, Wu Xuyang, Wang Qifan, Rajanala Sravanthi, Fang Yi
conference: "Arxiv"
year: 2024
bibkey: peng2024q
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.04522"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture', 'Prompting', 'Training Techniques']
---
Parameter Efficient Fine45;Tuning (PEFT) methods have been extensively utilized in Large Language Models (LLMs) to improve the down45;streaming tasks without the cost of fine45;tuing the whole LLMs. Recent studies have shown how to effectively use PEFT for fine45;tuning LLMs in ranking tasks with convincing performance; there are some limitations including the learned prompt being fixed for different documents overfitting to specific tasks and low adaptation ability. In this paper we introduce a query45;dependent parameter efficient fine45;tuning (Q45;PEFT) approach for text reranking to leak the information of the true queries to LLMs and then make the generation of true queries from input documents much easier. Specifically we utilize the query to extract the top45;k tokens from concatenated documents serving as contextual clues. We further augment Q45;PEFT by substituting the retrieval mechanism with a multi45;head attention layer to achieve end45;to45;end training and cover all the tokens in the documents guiding the LLMs to generate more document45;specific synthetic queries thereby further improving the reranking performance. Extensive experiments are conducted on four public datasets demonstrating the effectiveness of our proposed approach.
