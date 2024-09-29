---
layout: publication
title: Neuron Patching Semantic-based Neuron-level Language Model Repair For Code Generation
authors: Gu Jian, Aleti Aldeida, Chen Chunyang, Zhang Hongyu
conference: "Arxiv"
year: 2023
bibkey: gu2023neuron
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.05356"}
tags: ['Applications', 'Efficiency And Optimization', 'Reinforcement Learning', 'Tools']
---
Large Language Models (LLMs) have already gained widespread adoption in software engineering particularly in code generation tasks. However updating these models with new knowledge can be prohibitively expensive yet it is essential to maximize their utility such as implementing a hotfix technique to address urgent or critical LLM errors. In this paper we propose (textscMENT) a novel and effective model editing approach to repair LLMs in coding tasks. (textscMENT) is effective efficient and reliable capable of correcting a neural model by patching just one or two neurons. As pioneering work on neuron-level model editing of generative models we formalize the editing process and introduce the involved concepts. We also introduce new measures to evaluate its generalization ability and establish a benchmark for further study. Our approach is evaluated on three coding tasks line-level code generation shellcode generation and intent-to-bash translation. The experimental results demonstrate that the proposed approach significantly outperforms the state-of-the-art in both effectiveness and efficiency measures. Furthermore we showcase the applications of (textscMENT) for LLM reasoning in software engineering. By editing LLM knowledge the directly or indirectly dependent behaviors of API invocation in the chain-of-thought change accordingly. This illustrates the significance of repairing LLMs in the context of software engineering.
