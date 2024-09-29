---
layout: publication
title: 'Faith And Fate: Limits Of Transformers On Compositionality'
authors: Dziri Nouha, Lu Ximing, Sclar Melanie, Li Xiang Lorraine, Jiang Liwei, Lin Bill Yuchen, West Peter, Bhagavatula Chandra, Bras Ronan Le, Hwang Jena D., Sanyal Soumya, Welleck Sean, Ren Xiang, Ettinger Allyson, Harchaoui Zaid, Choi Yejin
conference: "Arxiv"
year: 2023
bibkey: dziri2023faith
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.18654"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Transformer']
---
Transformer large language models (LLMs) have sparked admiration for their exceptional performance on tasks that demand intricate multi-step reasoning. Yet these models simultaneously show failures on surprisingly trivial problems. This begs the question Are these errors incidental or do they signal more substantial limitations In an attempt to demystify transformer LLMs we investigate the limits of these models across three representative compositional tasks -- multi-digit multiplication logic grid puzzles and a classic dynamic programming problem. These tasks require breaking problems down into sub-steps and synthesizing these steps into a precise answer. We formulate compositional tasks as computation graphs to systematically quantify the level of complexity and break down reasoning steps into intermediate sub-procedures. Our empirical findings suggest that transformer LLMs solve compositional tasks by reducing multi-step compositional reasoning into linearized subgraph matching without necessarily developing systematic problem-solving skills. To round off our empirical study we provide theoretical arguments on abstract multi-step reasoning problems that highlight how autoregressive generations performance can rapidly decay withincreasedtaskcomplexity.
