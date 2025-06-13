---
layout: publication
title: 'Mathador-lm: A Dynamic Benchmark For Mathematical Reasoning On Large Language Models'
authors: Eldar Kurtic, Amir Moeini, Dan Alistarh
conference: "Arxiv"
year: 2024
bibkey: kurtic2024mathador
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.12572"}
  - {name: "Code", url: "https://github.com/IST-DASLab/Mathador-LM}{github.com/IST-DASLab/Mathador-LM"}
tags: ['RAG', 'Training Techniques', 'Has Code']
---
We introduce Mathador-LM, a new benchmark for evaluating the mathematical
reasoning on large language models (LLMs), combining ruleset interpretation,
planning, and problem-solving. This benchmark is inspired by the Mathador game,
where the objective is to reach a target number using basic arithmetic
operations on a given set of base numbers, following a simple set of rules. We
show that, across leading LLMs, we obtain stable average performance while
generating benchmark instances *dynamically*, following a target
difficulty level. Thus, our benchmark alleviates concerns about test-set
leakage into training data, an issue that often undermines popular benchmarks.
Additionally, we conduct a comprehensive evaluation of both open and
closed-source state-of-the-art LLMs on Mathador-LM. Our findings reveal that
contemporary models struggle with Mathador-LM, scoring significantly lower than
average 3rd graders. This stands in stark contrast to their strong performance
on popular mathematical reasoning benchmarks. The implementation of Mathador-LM
benchmark is available at
\href\{https://github.com/IST-DASLab/Mathador-LM\}\{github.com/IST-DASLab/Mathador-LM\}.
