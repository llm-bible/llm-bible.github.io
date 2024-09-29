---
layout: publication
title: Parameter-Efficient Tuning Large Language Models for Graph Representation Learning
authors: Zhu Qi, Zheng Da, Song Xiang, Zhang Shichang, Jin Bowen, Sun Yizhou, Karypis George
conference: "Arxiv"
year: 2024
bibkey: zhu2024parameter
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.18271"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Text-rich graphs which exhibit rich textual information on nodes and edges are prevalent across a wide range of real-world business applications. Large Language Models (LLMs) have demonstrated remarkable abilities in understanding text which also introduced the potential for more expressive modeling in text-rich graphs. Despite these capabilities efficiently applying LLMs to representation learning on graphs presents significant challenges. Recently parameter-efficient fine-tuning methods for LLMs have enabled efficient new task generalization with minimal time and memory consumption. Inspired by this we introduce Graph-aware Parameter-Efficient Fine-Tuning - GPEFT a novel approach for efficient graph representation learning with LLMs on text-rich graphs. Specifically we utilize a graph neural network (GNN) to encode structural information from neighboring nodes into a graph prompt. This prompt is then inserted at the beginning of the text sequence. To improve the quality of graph prompts we pre-trained the GNN to assist the frozen LLM in predicting the next token in the node text. Compared with existing joint GNN and LMs our method directly generate the node embeddings from large language models with an affordable fine-tuning cost. We validate our approach through comprehensive experiments conducted on 8 different text-rich graphs observing an average improvement of 2 in hit64;1 and Mean Reciprocal Rank (MRR) in link prediction evaluations. Our results demonstrate the efficacy and efficiency of our model showing that it can be smoothly integrated with various large language models including OPT LLaMA and Falcon.
