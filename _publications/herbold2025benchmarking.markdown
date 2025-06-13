---
layout: publication
title: 'Sortbench: Benchmarking Llms Based On Their Ability To Sort Lists'
authors: Steffen Herbold
conference: "Arxiv"
year: 2025
bibkey: herbold2025benchmarking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.08312'}
tags: ['Reinforcement Learning', 'GPT', 'Model Architecture']
---
Sorting is a tedious but simple task for human intelligence and can be solved
fairly easily algorithmically. However, for Large Language Models (LLMs) this
task is surprisingly hard, as some properties of sorting are among known
weaknesses of LLMs: being faithful to the input data, logical comparisons
between values, and strictly differentiating between syntax (used for sorting)
and semantics (typically learned by embeddings). Within this paper, we describe
the new SortBench benchmark for LLMs that comes with different difficulties and
that can be easily scaled in terms of difficulty. We apply this benchmark to
seven state-of-the-art LLMs, including current test-time reasoning models. Our
results show that while the o3-mini model is very capable at sorting in
general, even this can be fooled if strings are defined to mix syntactical and
semantical aspects, e.g., by asking to sort numbers written-out as word.
Furthermore, all models have problems with the faithfulness to the input of
long lists, i.e., they drop items and add new ones. Our results also show that
test-time reasoning has a tendency to overthink problems which leads to
performance degradation. Finally, models without test-time reasoning like
GPT-4o are not much worse than reasoning models.
