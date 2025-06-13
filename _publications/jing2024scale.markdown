---
layout: publication
title: 'On A Scale From 1 To 5: Quantifying Hallucination In Faithfulness Evaluation'
authors: Xiaonan Jing, Srinivas Billa, Danny Godbout
conference: "Arxiv"
year: 2024
bibkey: jing2024scale
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.12222"}
tags: ['GPT', 'Applications', 'Interpretability and Explainability', 'Model Architecture', 'Reinforcement Learning']
---
Hallucination has been a popular topic in natural language generation (NLG).
In real-world applications, unfaithful content can result in poor data quality
or loss of trust from end users. Thus, it is crucial to fact-check before
adopting NLG for production usage, which can be expensive if done manually. In
this paper, we investigate automated faithfulness evaluation in guided NLG. We
developed a rubric template and used large language models (LLMs) to score the
generation on quantifiable scales. We compared popular LLMs as well as widely
adopted natural language inference (NLI) models in scoring quality and
sensitivity. In addition, we developed methods for the generation of synthetic
unfaithful data, as well as heuristics to quantify the percentage of
hallucination. Our results on 4 travel-domain industry dataset show that GPT-4
can provide accurate judgement and explanation of whether a source and a
generation are factually consistent. Furthermore, we found that tuning NLI
models on synthetic data can improve performance. Lastly, we present insights
on the latency and cost of deploying such a system.
