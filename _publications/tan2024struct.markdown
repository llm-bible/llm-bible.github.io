---
layout: publication
title: 'Struct-x: Enhancing Large Language Models Reasoning With Structured Data'
authors: Tan Xiaoyu, Wang Haoyu, Qiu Xihe, Cheng Yuan, Xu Yinghui, Chu Wei, Qi Yuan
conference: "Arxiv"
year: 2024
bibkey: tan2024struct
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.12522"}
tags: ['Applications', 'Prompting', 'RAG', 'Tools', 'Training Techniques']
---
'Structured data, rich in logical and relational information, has the potential to enhance the reasoning abilities of large language models (LLMs). Still, its integration poses a challenge due to the risk of overwhelming LLMs with excessive tokens and irrelevant context information. To address this, we propose Struct-X, a novel framework that operates through five key phases: read-model-fill-reflect-reason'''' efficiently enabling LLMs to utilize structured data. It begins by encoding structured data into a topological space using graph embeddings, followed by filling in missing entity information with knowledge retrieval modules, and filtering out irrelevant tokens via a self-supervised module. The final phase involves constructing a topological network with selected tokens to further reduce the total token length for more effective LLM inference. Additionally, Struct-X includes an Auxiliary Module trained to generate prompts, aiding LLMs in analyzing structured data. Extensive experiments on benchmarks, including the knowledge graph question-answer task and the long document reading comprehension task, show that Struct-X notably improves LLM reasoning, demonstrating the effectiveness of structured data augmentation in improving LLM inference with complex input context.'
