---
layout: publication
title: 'Knowledgeable In-context Tuning: Exploring And Exploiting Factual Knowledge For In-context Learning'
authors: Wang Jianing, Wang Chengyu, Tan Chuanqi, Huang Jun, Gao Ming
conference: "Arxiv"
year: 2023
bibkey: wang2023knowledgeable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.14771"}
tags: ['Ethics And Bias', 'Few Shot', 'GPT', 'In Context Learning', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Tools', 'Training Techniques']
---
Large language models (LLMs) enable in-context learning (ICL) by conditioning on a few labeled training examples as a text-based prompt, eliminating the need for parameter updates and achieving competitive performance. In this paper, we demonstrate that factual knowledge is imperative for the performance of ICL in three core facets: the inherent knowledge learned in LLMs, the factual knowledge derived from the selected in-context examples, and the knowledge biases in LLMs for output generation. To unleash the power of LLMs in few-shot learning scenarios, we introduce a novel Knowledgeable In-Context Tuning (KICT) framework to further improve the performance of ICL: 1) injecting knowledge into LLMs during continual self-supervised pre-training, 2) judiciously selecting the examples for ICL with high knowledge relevance, and 3) calibrating the prediction results based on prior knowledge. We evaluate the proposed approaches on autoregressive models (e.g., GPT-style LLMs) over multiple text classification and question-answering tasks. Experimental results demonstrate that KICT substantially outperforms strong baselines and improves by more than 13&#37; and 7&#37; on text classification and question-answering tasks, respectively.
