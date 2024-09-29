---
layout: publication
title: LLM-augmented Preference Learning from Natural Language
authors: Kang Inwon, Ruan Sikai, Ho Tyler, Lin Jui-chien, Mohsin Farhad, Seneviratne Oshani, Xia Lirong
conference: "Arxiv"
year: 2023
bibkey: kang2023llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.08523"}
tags: ['Attention Mechanism', 'BERT', 'Few Shot', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques', 'Transformer']
---
Finding preferences expressed in natural language is an important but challenging task. State-of-the-art(SotA) methods leverage transformer-based models such as BERT RoBERTa etc. and graph neural architectures such as graph attention networks. Since Large Language Models (LLMs) are equipped to deal with larger context lengths and have much larger model sizes than the transformer-based model we investigate their ability to classify comparative text directly. This work aims to serve as a first step towards using LLMs for the CPC task. We design and conduct a set of experiments that format the classification task into an input prompt for the LLM and a methodology to get a fixed-format response that can be automatically evaluated. Comparing performances with existing methods we see that pre-trained LLMs are able to outperform the previous SotA models with no fine-tuning involved. Our results show that the LLMs can consistently outperform the SotA when the target text is large -- i.e. composed of multiple sentences -- and are still comparable to the SotA performance in shorter text. We also find that few-shot learning yields better performance than zero-shot learning.
