---
layout: publication
title: 'Can Many-shot In-context Learning Help Llms As Evaluators? A Preliminary Empirical Study'
authors: Mingyang Song, Mao Zheng, Xuan Luo, Yue Pan
conference: "Arxiv"
year: 2024
bibkey: song2024can
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.11629'}
tags: ['Attention Mechanism', 'Few-Shot', 'GPT', 'Model Architecture', 'Prompting', 'Ethics and Bias', 'In-Context Learning']
---
Utilizing Large Language Models (LLMs) as evaluators to assess the
performance of LLMs has garnered attention. However, this kind of evaluation
approach is affected by potential biases within LLMs, raising concerns about
the accuracy and reliability of the evaluation results of LLMs. To address this
problem, we propose and study two many-shot In-Context Learning (ICL) prompt
templates to help LLM evaluators mitigate potential biases: Many-Shot with
Reference (MSwR) and Many-Shot without Reference (MSoR). Specifically, the
former utilizes in-context examples with model-generated evaluation rationales
as references, while the latter does not include these references. Using these
prompt designs, we investigate the impact of increasing the number of
in-context examples on the consistency and quality of the evaluation results.
Experimental results show that advanced LLMs, such as GPT-4o, perform better in
the many-shot regime than in the zero-shot and few-shot regimes. Furthermore,
when using GPT-4o as an evaluator in the many-shot regime, adopting MSwR as the
prompt template performs better than MSoR.
