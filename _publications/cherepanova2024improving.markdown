---
layout: publication
title: 'Improving LLM Group Fairness On Tabular Data Via In-context Learning'
authors: Valeriia Cherepanova, Chia-jung Lee, Nil-jana Akpinar, Riccardo Fogliato, Martin Andres Bertran, Michael Kearns, James Zou
conference: "Arxiv"
year: 2024
bibkey: cherepanova2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.04642"}
tags: ['Efficiency and Optimization', 'Ethics and Bias', 'RAG', 'Bias Mitigation', 'Few-Shot', 'Fairness', 'Prompting', 'In-Context Learning']
---
Large language models (LLMs) have been shown to be effective on tabular
prediction tasks in the low-data regime, leveraging their internal knowledge
and ability to learn from instructions and examples. However, LLMs can fail to
generate predictions that satisfy group fairness, that is, produce equitable
outcomes across groups. Critically, conventional debiasing approaches for
natural language tasks do not directly translate to mitigating group unfairness
in tabular settings. In this work, we systematically investigate four empirical
approaches to improve group fairness of LLM predictions on tabular datasets,
including fair prompt optimization, soft prompt tuning, strategic selection of
few-shot examples, and self-refining predictions via chain-of-thought
reasoning. Through experiments on four tabular datasets using both open-source
and proprietary LLMs, we show the effectiveness of these methods in enhancing
demographic parity while maintaining high overall performance. Our analysis
provides actionable insights for practitioners in selecting the most suitable
approach based on their specific requirements and constraints.
