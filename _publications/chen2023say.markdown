---
layout: publication
title: 'Say What You Mean! Large Language Models Speak Too Positively About Negative Commonsense Knowledge'
authors: Jiangjie Chen, Wei Shi, Ziquan Fu, Sijie Cheng, Lei Li, Yanghua Xiao
conference: "Arxiv"
year: 2023
bibkey: chen2023say
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.05976"}
tags: ['Pre-Training', 'Ethics and Bias', 'Language Modeling', 'Reinforcement Learning', 'Training Techniques']
---
Large language models (LLMs) have been widely studied for their ability to
store and utilize positive knowledge. However, negative knowledge, such as
"lions don't live in the ocean", is also ubiquitous in the world but rarely
mentioned explicitly in the text. What do LLMs know about negative knowledge?
This work examines the ability of LLMs to negative commonsense knowledge. We
design a constrained keywords-to-sentence generation task (CG) and a Boolean
question-answering task (QA) to probe LLMs. Our experiments reveal that LLMs
frequently fail to generate valid sentences grounded in negative commonsense
knowledge, yet they can correctly answer polar yes-or-no questions. We term
this phenomenon the belief conflict of LLMs. Our further analysis shows that
statistical shortcuts and negation reporting bias from language modeling
pre-training cause this conflict.
