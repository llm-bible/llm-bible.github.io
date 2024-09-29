---
layout: publication
title: Large Language Models Are Inconsistent And Biased Evaluators
authors: Stureborg Rickard, Alikaniotis Dimitris, Suhara Yoshi
conference: "Arxiv"
year: 2024
bibkey: stureborg2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.01724"}
tags: ['Ethics And Bias', 'Prompting', 'Security', 'Tools']
---
The zero45;shot capability of Large Language Models (LLMs) has enabled highly flexible reference45;free metrics for various tasks making LLM evaluators common tools in NLP. However the robustness of these LLM evaluators remains relatively understudied; existing work mainly pursued optimal performance in terms of correlating LLM scores with human expert scores. In this paper we conduct a series of analyses using the SummEval dataset and confirm that LLMs are biased evaluators as they (1) exhibit familiarity bias45;a preference for text with lower perplexity (2) show skewed and biased distributions of ratings and (3) experience anchoring effects for multi45;attribute judgments. We also found that LLMs are inconsistent evaluators showing low inter45;sample agreement and sensitivity to prompt differences that are insignificant to human understanding of text quality. Furthermore we share recipes for configuring LLM evaluators to mitigate these limitations. Experimental results on the RoSE dataset demonstrate improvements over the state45;of45;the45;art LLM evaluators.
