---
layout: publication
title: 'Are Llms Really Not Knowledgable? Mining The Submerged Knowledge In Llms'' Memory'
authors: Xingjian Tao, Yiwei Wang, Yujun Cai, Zhicheng Yang, Jing Tang
conference: "Arxiv"
year: 2024
bibkey: tao2024are
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.20846"}
tags: ['RAG', 'Training Techniques']
---
Large language models (LLMs) have shown promise as potential knowledge bases,
yet they often struggle with question-answering tasks and are prone to
hallucinations. While previous research attributes these issues to knowledge
gaps in the model's parameters, our investigation reveals a different
phenomenon: LLMs often retain correct knowledge even when generating incorrect
answers. Through analysis of model's internal representations, we find that
correct answers frequently appear among high-probability tokens despite not
being selected as final outputs. Based on this observation, we introduce
Hits@k, a new metric to assess knowledge retention independent of expression
accuracy. Our extensive experiments demonstrate that LLMs store significantly
more knowledge than their QA performance suggests. Building on these findings,
we develop SkipUnsure, a method to improve answer accuracy by leveraging
detected but unexpressed knowledge. Experiments on both open-domain and
specific-domain datasets show consistent improvements, with accuracy gains of
up to 11.8% on DBPedia and 6.3% on IMDB, without requiring model retraining.
