---
layout: publication
title: 'Hypoeval: Hypothesis-guided Evaluation For Natural Language Generation'
authors: Mingxuan Li, Hanchen Li, Chenhao Tan
conference: "Arxiv"
year: 2025
bibkey: li2025hypothesis
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.07174"}
tags: ['RAG', 'Tools', 'Security']
---
Large language models (LLMs) have demonstrated great potential for automating
the evaluation of natural language generation. Previous frameworks of
LLM-as-a-judge fall short in two ways: they either use zero-shot setting
without consulting any human input, which leads to low alignment, or fine-tune
LLMs on labeled data, which requires a non-trivial number of samples. Moreover,
previous methods often provide little reasoning behind automated evaluations.
In this paper, we propose HypoEval, Hypothesis-guided Evaluation framework,
which first uses a small corpus of human evaluations to generate more detailed
rubrics for human judgments and then incorporates a checklist-like approach to
combine LLM's assigned scores on each decomposed dimension to acquire overall
scores. With only 30 human evaluations, HypoEval achieves state-of-the-art
performance in alignment with both human rankings (Spearman correlation) and
human scores (Pearson correlation), on average outperforming G-Eval by 11.86%
and fine-tuned Llama-3.1-8B-Instruct with at least 3 times more human
evaluations by 11.95%. Furthermore, we conduct systematic studies to assess the
robustness of HypoEval, highlighting its effectiveness as a reliable and
interpretable automated evaluation framework.
