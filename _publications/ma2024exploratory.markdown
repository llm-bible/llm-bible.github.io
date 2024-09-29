---
layout: publication
title: Llmparser An Exploratory Study On Using Large Language Models For Log Parsing
authors: Ma Zeyang, Chen An Ran, Kim Dong Jae, Chen Tse-hsun, Wang Shaowei
conference: "Arxiv"
year: 2024
bibkey: ma2024exploratory
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.18001"}
tags: ['Fine Tuning', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Logs are important in modern software development with runtime information. Log parsing is the first step in many log45;based analyses that involve extracting structured information from unstructured log data. Traditional log parsers face challenges in accurately parsing logs due to the diversity of log formats which directly impacts the performance of downstream log45;analysis tasks. In this paper we explore the potential of using Large Language Models (LLMs) for log parsing and propose LLMParser an LLM45;based log parser based on generative LLMs and few45;shot tuning. We leverage four LLMs Flan45;T545;small Flan45;T545;base LLaMA45;7B and ChatGLM45;6B in LLMParsers. Our evaluation of 16 open45;source systems shows that LLMParser achieves statistically significantly higher parsing accuracy than state45;of45;the45;art parsers (a 9637; average parsing accuracy). We further conduct a comprehensive empirical analysis on the effect of training size model size and pre45;training LLM on log parsing accuracy. We find that smaller LLMs may be more effective than more complex LLMs; for instance where Flan45;T545;base achieves comparable results as LLaMA45;7B with a shorter inference time. We also find that using LLMs pre45;trained using logs from other systems does not always improve parsing accuracy. While using pre45;trained Flan45;T545;base shows an improvement in accuracy pre45;trained LLaMA results in a decrease (decrease by almost 5537; in group accuracy). In short our study provides empirical evidence for using LLMs for log parsing and highlights the limitations and future research direction of LLM45;based log parsers.
