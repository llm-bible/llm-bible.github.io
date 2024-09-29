---
layout: publication
title: Mitigating Misleading Chain-of-thought Reasoning With Selective Filtering
authors: Wu Yexin, Zhang Zhuosheng, Zhao Hai
conference: "Arxiv"
year: 2024
bibkey: wu2024mitigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.19167"}
  - {name: "Code", url: "https://github.com/LibroWu/SelF-Reasoner"}
tags: ['Has Code', 'Pretraining Methods', 'RAG', 'Reinforcement Learning']
---
Large language models have manifested remarkable capabilities by leveraging chain-of-thought (CoT) reasoning techniques to solve intricate questions through step-by-step reasoning chains. Despite its success the efficacy of such reasoning is inherently contingent upon the quality of CoT. However flawless CoT reasoning cannot be guaranteed due to the presence of indecomposable questions and the potential for erroneous reasoning chains particularly in the case of small-scale language models. To tackle this challenge we propose a novel approach called the selective filtering reasoner (SelF-Reasoner) that assesses the entailment relationship between the question and the candidate reasoning chain. Then we proceed with CoT reasoning when the reasoning chain demonstrates confidence; otherwise we opt to predict the answer directly. SelF-Reasoner improves the fine-tuned T5 baseline consistently over the ScienceQA ECQA and LastLetter tasks. Code is available at texttthttps://github.com/LibroWu/SelF-Reasoner}.
