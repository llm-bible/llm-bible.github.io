---
layout: publication
title: 'Automatic Legal Writing Evaluation Of Llms'
authors: Ramon Pires, Roseval Malaquias Junior, Rodrigo Nogueira
conference: "Arxiv"
year: 2025
bibkey: pires2025automatic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.21202'}
tags: ['RAG']
---
Despite the recent advances in Large Language Models, benchmarks for
evaluating legal writing remain scarce due to the inherent complexity of
assessing open-ended responses in this domain. One of the key challenges in
evaluating language models on domain-specific tasks is finding test datasets
that are public, frequently updated, and contain comprehensive evaluation
guidelines. The Brazilian Bar Examination meets these requirements. We
introduce oab-bench, a benchmark comprising 105 questions across seven areas of
law from recent editions of the exam. The benchmark includes comprehensive
evaluation guidelines and reference materials used by human examiners to ensure
consistent grading. We evaluate the performance of four LLMs on oab-bench,
finding that Claude-3.5 Sonnet achieves the best results with an average score
of 7.93 out of 10, passing all 21 exams. We also investigated whether LLMs can
serve as reliable automated judges for evaluating legal writing. Our
experiments show that frontier models like OpenAI's o1 achieve a strong
correlation with human scores when evaluating approved exams, suggesting their
potential as reliable automated evaluators despite the inherently subjective
nature of legal writing assessment. The source code and the benchmark --
containing questions, evaluation guidelines, model-generated responses, and
their respective automated evaluations -- are publicly available.
