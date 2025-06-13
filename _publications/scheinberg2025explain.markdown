---
layout: publication
title: 'Explain-then-process: Using Grammar Prompting To Enhance Grammatical Acceptability Judgments'
authors: Russell Scheinberg, Ameeta Agrawal, Amber Shore, So Young Lee
conference: "Arxiv"
year: 2025
bibkey: scheinberg2025explain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.02302"}
tags: ['Prompting', 'RAG', 'Interpretability and Explainability']
---
Large language models (LLMs) can explain grammatical rules, yet they often fail to apply those rules when judging sentence acceptability. We present "grammar prompting", an explain-then-process paradigm: a large LLM first produces a concise explanation of the relevant syntactic phenomenon, then that explanation is fed back as additional context to the target model -- either an LLM or a smaller language model (SLM) -- before deciding which sentence of a minimal pair is grammatical. On the English BLiMP, Chinese SLING, and Russian RuBLiMP benchmarks, this simple prompt design yields substantial improvements over strong baselines across many syntactic phenomena. Feeding an LLM's metalinguistic explanation back to the target model bridges the gap between knowing a rule and using it. On SLMs, grammar prompting alone trims the average LLM-SLM accuracy gap by about 20%, and when paired with chain-of-thought, by 56% (13.0 pp -> 5.8 pp), all at negligible cost. The lightweight, language-agnostic cue lets low-cost SLMs approach frontier-LLM performance in multilingual settings.
