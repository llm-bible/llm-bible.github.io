---
layout: publication
title: OLMES: A Standard For Language Model Evaluations
authors: Gu Yuling, Tafjord Oyvind, Kuehl Bailey, Haddad Dany, Dodge Jesse, Hajishirzi Hannaneh
conference: "Arxiv"
year: 2024
bibkey: gu2024standard
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.08446"}
tags: ['Model Architecture', 'Prompting', 'Reinforcement Learning', 'Survey Paper']
---
Progress in AI is often demonstrated by new models claiming improved performance on tasks measuring model capabilities. Evaluating language models in particular is challenging as small changes to how a model is evaluated on a task can lead to large changes in measured performance. There is no common standard setup so different models are evaluated on the same tasks in different ways leading to claims about which models perform best not being reproducible. We propose OLMES a completely documented practical open standard for reproducible LLM evaluations. In developing this standard we identify and review the varying factors in evaluation practices adopted by the community - such as details of prompt formatting choice of in-context examples probability normalizations and task formulation. In particular OLMES supports meaningful comparisons between smaller base models that require the unnatural cloze formulation of multiple-choice questions against larger models that can utilize the original formulation. OLMES includes well-considered recommendations guided by results from existing literature as well as new experiments investigating open questions.
