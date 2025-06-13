---
layout: publication
title: 'Retrieval Augmented Generation (RAG) And Beyond: A Comprehensive Survey On How To Make Your Llms Use External Data More Wisely'
authors: Siyun Zhao, Yuqing Yang, Zilong Wang, Zhiyuan He, Luna K. Qiu, Lili Qiu
conference: "Arxiv"
year: 2024
bibkey: zhao2024retrieval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.14924"}
tags: ['Training Techniques', 'Model Architecture', 'Survey Paper', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Applications', 'Attention Mechanism']
---
Large language models (LLMs) augmented with external data have demonstrated
remarkable capabilities in completing real-world tasks. Techniques for
integrating external data into LLMs, such as Retrieval-Augmented Generation
(RAG) and fine-tuning, are gaining increasing attention and widespread
application. Nonetheless, the effective deployment of data-augmented LLMs
across various specialized fields presents substantial challenges. These
challenges encompass a wide range of issues, from retrieving relevant data and
accurately interpreting user intent to fully harnessing the reasoning
capabilities of LLMs for complex tasks. We believe that there is no
one-size-fits-all solution for data-augmented LLM applications. In practice,
underperformance often arises from a failure to correctly identify the core
focus of a task or because the task inherently requires a blend of multiple
capabilities that must be disentangled for better resolution. In this survey,
we propose a RAG task categorization method, classifying user queries into four
levels based on the type of external data required and primary focus of the
task: explicit fact queries, implicit fact queries, interpretable rationale
queries, and hidden rationale queries. We define these levels of queries,
provide relevant datasets, and summarize the key challenges and most effective
techniques for addressing these challenges. Finally, we discuss three main
forms of integrating external data into LLMs: context, small model, and
fine-tuning, highlighting their respective strengths, limitations, and the
types of problems they are suited to solve. This work aims to help readers
thoroughly understand and decompose the data requirements and key bottlenecks
in building LLM applications, offering solutions to the different challenges
and serving as a guide to systematically developing such applications.
