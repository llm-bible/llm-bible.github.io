---
layout: publication
title: Citation45;enhanced Generation For Llm45;based Chatbots
authors: Li Weitao, Li Junkai, Ma Weizhi, Liu Yang
conference: "Arxiv"
year: 2024
bibkey: li2024citation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.16063"}
tags: ['Agentic', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large language models (LLMs) exhibit powerful general intelligence across diverse scenarios including their integration into chatbots. However a vital challenge of LLM45;based chatbots is that they may produce hallucinated content in responses which significantly limits their applicability. Various efforts have been made to alleviate hallucination such as retrieval augmented generation and reinforcement learning with human feedback but most of them require additional training and data annotation. In this paper we propose a novel post45;hoc Citation45;Enhanced Generation (CEG) approach combined with retrieval argumentation. Unlike previous studies that focus on preventing hallucinations during generation our method addresses this issue in a post45;hoc way. It incorporates a retrieval module to search for supporting documents relevant to the generated content and employs a natural language inference45;based citation generation module. Once the statements in the generated content lack of reference our model can regenerate responses until all statements are supported by citations. Note that our method is a training45;free plug45;and45;play plugin that is capable of various LLMs. Experiments on various hallucination45;related datasets show our framework outperforms state45;of45;the45;art methods in both hallucination detection and response regeneration on three benchmarks. Our codes and dataset will be publicly available.
