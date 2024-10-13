---
layout: publication
title: 'Large Language Models As Evaluators For Recommendation Explanations'
authors: Zhang Xiaoyu, Li Yishan, Wang Jiayin, Sun Bowen, Ma Weizhi, Sun Peijie, Zhang Min
conference: "Arxiv"
year: 2024
bibkey: zhang2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.03248"}
  - {name: "Code", url: "https://github.com/Xiaoyu-SZ/LLMasEvaluator"}
tags: ['Attention Mechanism', 'GPT', 'Has Code', 'Interpretability And Explainability', 'Merging', 'Model Architecture', 'Prompting', 'RAG']
---
The explainability of recommender systems has attracted significant attention
in academia and industry. Many efforts have been made for explainable
recommendations, yet evaluating the quality of the explanations remains a
challenging and unresolved issue. In recent years, leveraging LLMs as
evaluators presents a promising avenue in Natural Language Processing tasks
(e.g., sentiment classification, information extraction), as they perform
strong capabilities in instruction following and common-sense reasoning.
However, evaluating recommendation explanatory texts is different from these
NLG tasks, as its criteria are related to human perceptions and are usually
subjective. In this paper, we investigate whether LLMs can serve as evaluators
of recommendation explanations. To answer the question, we utilize real user
feedback on explanations given from previous work and additionally collect
third-party annotations and LLM evaluations. We design and apply a 3-level meta
evaluation strategy to measure the correlation between evaluator labels and the
ground truth provided by users. Our experiments reveal that LLMs, such as GPT4,
can provide comparable evaluations with appropriate prompts and settings. We
also provide further insights into combining human labels with the LLM
evaluation process and utilizing ensembles of multiple heterogeneous LLM
evaluators to enhance the accuracy and stability of evaluations. Our study
verifies that utilizing LLMs as evaluators can be an accurate, reproducible and
cost-effective solution for evaluating recommendation explanation texts. Our
code is available at https://github.com/Xiaoyu-SZ/LLMasEvaluator.
