---
layout: publication
title: Reflection Of Thought Inversely Eliciting Numerical Reasoning In Language Models Via Solving Linear Systems
authors: Zhou Fan, Dong Haoyu, Liu Qian, Cheng Zhoujun, Han Shi, Zhang Dongmei
conference: "Arxiv"
year: 2022
bibkey: zhou2022reflection
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.05075"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Numerical reasoning over natural language has been a long45;standing goal for the research community. However cutting45;edge language models have proven difficult to reliably generalize to a broad range of numbers although they have shown proficiency in reasoning over common and simple numbers. In this paper we propose a novel method to elicit and exploit the numerical reasoning knowledge hidden in pre45;trained language models using simple anchor numbers. Concretely we first leverage simple numbers as anchors to probe the implicitly inferred arithmetic expressions from language models and then explicitly apply the expressions on complex numbers to get corresponding answers. To inversely elicit arithmetic expressions we transform and formulate the task as an analytically solvable linear system. Experimental results on several numerical reasoning benchmarks demonstrate that our approach significantly improves numerical reasoning capabilities of existing LMs. More importantly our approach is training45;free and simply works in the inference phase making it highly portable and achieving consistent performance benefits across a variety of language models (GPT45;3 T5 BART etc) in all zero45;shot few45;shot and fine45;tuning scenarios.
