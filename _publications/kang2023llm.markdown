---
layout: publication
title: Llm45;augmented Preference Learning From Natural Language
authors: Kang Inwon, Ruan Sikai, Ho Tyler, Lin Jui-chien, Mohsin Farhad, Seneviratne Oshani, Xia Lirong
conference: "Arxiv"
year: 2023
bibkey: kang2023llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.08523"}
tags: ['Attention Mechanism', 'BERT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Transformer']
---
Finding preferences expressed in natural language is an important but challenging task. State45;of45;the45;art(SotA) methods leverage transformer45;based models such as BERT RoBERTa etc. and graph neural architectures such as graph attention networks. Since Large Language Models (LLMs) are equipped to deal with larger context lengths and have much larger model sizes than the transformer45;based model we investigate their ability to classify comparative text directly. This work aims to serve as a first step towards using LLMs for the CPC task. We design and conduct a set of experiments that format the classification task into an input prompt for the LLM and a methodology to get a fixed45;format response that can be automatically evaluated. Comparing performances with existing methods we see that pre45;trained LLMs are able to outperform the previous SotA models with no fine45;tuning involved. Our results show that the LLMs can consistently outperform the SotA when the target text is large 45;45; i.e. composed of multiple sentences 45;45; and are still comparable to the SotA performance in shorter text. We also find that few45;shot learning yields better performance than zero45;shot learning.
