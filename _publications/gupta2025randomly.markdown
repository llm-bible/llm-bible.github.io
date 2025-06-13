---
layout: publication
title: 'Randomly Sampled Language Reasoning Problems Explain Limits Of Llms'
authors: Kavi Gupta, Kate Sanders, Armando Solar-lezama
conference: "Arxiv"
year: 2025
bibkey: gupta2025randomly
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.02825"}
tags: ['GPT', 'Ethics and Bias', 'Merging', 'Reinforcement Learning', 'Pretraining Methods', 'Prompting']
---
While LLMs have revolutionized the field of machine learning due to their high performance across a range of tasks, they are known to perform poorly in planning, hallucinate false answers, have degraded performance on less canonical versions of the same task, and answer incorrectly on a variety of specific prompts. There are several emerging theories of LLM performance with some predictive power, among them that LLMs lack world modeling ability, that they have an undesirable bias towards an autoregressive prior, and that they perform less well on more novel problems. The existing literature on novelty has focused on tasks of relatively high complexity, studying perturbations of canonical but complex problems. In this paper, we attempt to isolate novelty as a factor in LLM underperformance. To this end, we consider an extremely simple domain: next token prediction on simple language tasks. The twist is that these language tasks are unseen, as they are randomly drawn from a large, parsimoniously defined set of languages arising from simple grammar rules. This allows us to isolate the effect of task novelty and see if it is sufficient to explain low performance. We find that LLMs uniformly underperform n-gram models (which do not have the capacity for world modeling) on these tasks, both when used as next token predictors and as reasoners.
