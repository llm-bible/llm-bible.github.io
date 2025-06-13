---
layout: publication
title: 'Know Or Not: A Library For Evaluating Out-of-knowledge Base Robustness'
authors: Jessica Foo, Pradyumna Shyama Prasad, Shaun Khoo
conference: "Arxiv"
year: 2025
bibkey: foo2025know
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.13545"}
  - {name: "Code", url: "https://github.com/govtech-responsibleai/KnowOrNot"}
tags: ['Tools', 'Applications', 'RAG', 'Model Architecture', 'Security', 'Has Code']
---
While the capabilities of large language models (LLMs) have progressed significantly, their use in high-stakes applications have been limited due to risks of hallucination. One key approach in reducing hallucination is retrieval-augmented generation (RAG), but even in such setups, LLMs may still hallucinate when presented with questions outside of the knowledge base. Such behavior is unacceptable in high-stake applications where LLMs are expected to abstain from answering queries it does not have sufficient context on. In this work, we present a novel methodology for systematically evaluating out-of-knowledge base (OOKB) robustness of LLMs (whether LLMs know or do not know) in the RAG setting, without the need for manual annotation of gold standard answers. We implement our methodology in knowornot, an open-source library that enables users to develop their own customized evaluation data and pipelines for OOKB robustness. knowornot comprises four main features. Firstly, it provides a unified, high-level API that streamlines the process of setting up and running robustness benchmarks. Secondly, its modular architecture emphasizes extensibility and flexibility, allowing users to easily integrate their own LLM clients and RAG settings. Thirdly, its rigorous data modeling design ensures experiment reproducibility, reliability and traceability. Lastly, it implements a comprehensive suite of tools for users to customize their pipelines. We demonstrate the utility of knowornot by developing a challenging benchmark, PolicyBench, which spans four Question-Answer (QA) chatbots on government policies, and analyze its OOKB robustness. The source code of knowornot is available https://github.com/govtech-responsibleai/KnowOrNot.
