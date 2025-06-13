---
layout: publication
title: 'Self-reflective Planning With Knowledge Graphs: Enhancing LLM Reasoning Reliability For Question Answering'
authors: Jiajun Zhu, Ye Liu, Meikai Bao, Kai Zhang, Yanghai Zhang, Qi Liu
conference: "Arxiv"
year: 2025
bibkey: zhu2025self
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.19410'}
tags: ['Applications', 'Tools']
---
Recently, large language models (LLMs) have demonstrated remarkable capabilities in natural language processing tasks, yet they remain prone to hallucinations when reasoning with insufficient internal knowledge. While integrating LLMs with knowledge graphs (KGs) provides access to structured, verifiable information, existing approaches often generate incomplete or factually inconsistent reasoning paths. To this end, we propose Self-Reflective Planning (SRP), a framework that synergizes LLMs with KGs through iterative, reference-guided reasoning. Specifically, given a question and topic entities, SRP first searches for references to guide planning and reflection. In the planning process, it checks initial relations and generates a reasoning path. After retrieving knowledge from KGs through a reasoning path, it implements iterative reflection by judging the retrieval result and editing the reasoning path until the answer is correctly retrieved. Extensive experiments on three public datasets demonstrate that SRP surpasses various strong baselines and further underscore its reliable reasoning ability.
