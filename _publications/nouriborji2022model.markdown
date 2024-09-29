---
layout: publication
title: Minialbert Model Distillation Via Parameter45;efficient Recursive Transformers
authors: Nouriborji Mohammadmahdi, Rohanian Omid, Kouchaki Samaneh, Clifton David A.
conference: "Arxiv"
year: 2022
bibkey: nouriborji2022model
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.06425"}
  - {name: "Code", url: "https://github.com/nlpie&#45;research/MiniALBERT"}
  - {name: "Code", url: "https://huggingface.co/nlpie"}
tags: ['Applications', 'BERT', 'Distillation', 'Efficiency And Optimization', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Transformer']
---
Pre45;trained Language Models (LMs) have become an integral part of Natural Language Processing (NLP) in recent years due to their superior performance in downstream applications. In spite of this resounding success the usability of LMs is constrained by computational and time complexity along with their increasing size; an issue that has been referred to as overparameterisation. Different strategies have been proposed in the literature to alleviate these problems with the aim to create effective compact models that nearly match the performance of their bloated counterparts with negligible performance losses. One of the most popular techniques in this area of research is model distillation. Another potent but underutilised technique is cross45;layer parameter sharing. In this work we combine these two strategies and present MiniALBERT a technique for converting the knowledge of fully parameterised LMs (such as BERT) into a compact recursive student. In addition we investigate the application of bottleneck adapters for layer45;wise adaptation of our recursive student and also explore the efficacy of adapter tuning for fine45;tuning of compact models. We test our proposed models on a number of general and biomedical NLP tasks to demonstrate their viability and compare them with the state45;of45;the45;art and other existing compact models. All the codes used in the experiments are available at https://github.com/nlpie&#45;research/MiniALBERT. Our pre45;trained compact models can be accessed from https://huggingface.co/nlpie.
