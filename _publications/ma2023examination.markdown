---
layout: publication
title: 'An Examination Of The Compositionality Of Large Generative Vision-language Models'
authors: Teli Ma, Rong Li, Junwei Liang
conference: "Arxiv"
year: 2023
bibkey: ma2023examination
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.10509"}
  - {name: "Code", url: "https://github.com/TeleeMa/SADE)"}
tags: ['Security', 'Model Architecture', 'Multimodal Models', 'RAG', 'GPT', 'Ethics and Bias', 'Has Code']
---
With the success of Large Language Models (LLMs), many Generative
Vision-Language Models (GVLMs) have been constructed via multimodal instruction
tuning. However, the performance of GVLMs in multimodal compositional reasoning
remains under-explored. In this paper, we examine both the evaluation metrics
(VisualGPTScore, etc.) and current benchmarks for evaluating the
compositionality of GVLMs. We identify the syntactical bias in current
benchmarks, which is exploited by the linguistic capability of GVLMs. The bias
renders VisualGPTScore an insufficient metric for assessing GVLMs. To combat
this, we first introduce a SyntaxBias Score, leveraging LLMs to quantify such
bias for mitigation. A challenging new task is subsequently added to evaluate
the robustness of GVLMs against inherent inclination toward syntactical
correctness. Using the bias-mitigated datasets and the new task, we propose a
novel benchmark, namely SyntActically DE-biased benchmark (SADE). Our study
provides an unbiased benchmark for the compositionality of GVLMs, facilitating
future research in this direction (Code and dataset are available at
https://github.com/TeleeMa/SADE).
