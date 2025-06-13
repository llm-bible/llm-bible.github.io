---
layout: publication
title: 'Exploring The Effectiveness And Interpretability Of Texts In Llm-based Time Series Models'
authors: Zhengke Sun, Hangwei Qian, Ivor Tsang
conference: "Arxiv"
year: 2025
bibkey: sun2025exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.08808"}
  - {name: "Code", url: "https://github.com/zachysun/TS-Lang-Exp"}
tags: ['Tools', 'RAG', 'Has Code', 'Interpretability and Explainability', 'Prompting']
---
Large Language Models (LLMs) have been applied to time series forecasting
tasks, leveraging pre-trained language models as the backbone and incorporating
textual data to purportedly enhance the comprehensive capabilities of LLMs for
time series. However, are these texts really helpful for interpretation? This
study seeks to investigate the actual efficacy and interpretability of such
textual incorporations. Through a series of empirical experiments on textual
prompts and textual prototypes, our findings reveal that the misalignment
between two modalities exists, and the textual information does not
significantly improve time series forecasting performance in many cases.
Furthermore, visualization analysis indicates that the textual representations
learned by existing frameworks lack sufficient interpretability when applied to
time series data. We further propose a novel metric named Semantic Matching
Index (SMI) to better evaluate the matching degree between time series and
texts during our post hoc interpretability investigation. Our analysis reveals
the misalignment and limited interpretability of texts in current time-series
LLMs, and we hope this study can raise awareness of the interpretability of
texts for time series. The code is available at
https://github.com/zachysun/TS-Lang-Exp.
