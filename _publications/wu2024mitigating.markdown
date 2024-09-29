---
layout: publication
title: Mitigating Misleading Chain45;of45;thought Reasoning With Selective Filtering
authors: Wu Yexin, Zhang Zhuosheng, Zhao Hai
conference: "Arxiv"
year: 2024
bibkey: wu2024mitigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.19167"}
  - {name: "Code", url: "https://github.com/LibroWu/SelF&#45;Reasoner&#125;"}
tags: ['Has Code', 'Pretraining Methods', 'RAG', 'Reinforcement Learning']
---
Large language models have manifested remarkable capabilities by leveraging chain45;of45;thought (CoT) reasoning techniques to solve intricate questions through step45;by45;step reasoning chains. Despite its success the efficacy of such reasoning is inherently contingent upon the quality of CoT. However flawless CoT reasoning cannot be guaranteed due to the presence of indecomposable questions and the potential for erroneous reasoning chains particularly in the case of small45;scale language models. To tackle this challenge we propose a novel approach called the selective filtering reasoner (SelF45;Reasoner) that assesses the entailment relationship between the question and the candidate reasoning chain. Then we proceed with CoT reasoning when the reasoning chain demonstrates confidence; otherwise we opt to predict the answer directly. SelF45;Reasoner improves the fine45;tuned T5 baseline consistently over the ScienceQA ECQA and LastLetter tasks. Code is available at texttt123;https://github.com/LibroWu/SelF&#45;Reasoner&#125;.
