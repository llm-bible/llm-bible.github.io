---
layout: publication
title: 'Fltlm: An Intergrated Long-context Large Language Model For Effective Context Filtering And Understanding'
authors: Jingyang Deng, Zhengyang Shen, Boyang Wang, Lixin Su, Suqi Cheng, Ying Nie, Junfeng Wang, Dawei Yin, Jinwen Ma
conference: "Arxiv"
year: 2024
bibkey: deng2024intergrated
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.06886"}
tags: ['Training Techniques', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
The development of Long-Context Large Language Models (LLMs) has markedly
advanced natural language processing by facilitating the process of textual
data across long documents and multiple corpora. However, Long-Context LLMs
still face two critical challenges: The lost in the middle phenomenon, where
crucial middle-context information is likely to be missed, and the distraction
issue that the models lose focus due to overly extended contexts. To address
these challenges, we propose the Context Filtering Language Model (FltLM), a
novel integrated Long-Context LLM which enhances the ability of the model on
multi-document question-answering (QA) tasks. Specifically, FltLM innovatively
incorporates a context filter with a soft mask mechanism, identifying and
dynamically excluding irrelevant content to concentrate on pertinent
information for better comprehension and reasoning. Our approach not only
mitigates these two challenges, but also enables the model to operate
conveniently in a single forward pass. Experimental results demonstrate that
FltLM significantly outperforms supervised fine-tuning and retrieval-based
methods in complex QA scenarios, suggesting a promising solution for more
accurate and reliable long-context natural language understanding applications.
