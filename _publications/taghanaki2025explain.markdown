---
layout: publication
title: 'Explain-query-test: Self-evaluating Llms Via Explanation And Comprehension Discrepancy'
authors: Saeid Asgari Taghanaki, Joao Monteiro
conference: "Arxiv"
year: 2025
bibkey: taghanaki2025explain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.11721"}
  - {name: "Code", url: "https://github.com/asgsaeid/EQT"}
tags: ['Interpretability and Explainability', 'Has Code']
---
Large language models (LLMs) have demonstrated remarkable proficiency in
generating detailed and coherent explanations of complex concepts. However, the
extent to which these models truly comprehend the concepts they articulate
remains unclear. To assess the level of comprehension of a model relative to
the content it generates, we implemented a self-evaluation pipeline where
models: (i) given a topic generate an excerpt with information about the topic,
(ii) given an excerpt generate question-answer pairs, and finally (iii) given a
question generate an answer. We refer to this self-evaluation approach as
Explain-Query-Test (EQT). Interestingly, the accuracy on generated questions
resulting from running the EQT pipeline correlates strongly with the model
performance as verified by typical benchmarks such as MMLU-Pro. In other words,
EQT's performance is predictive of MMLU-Pro's, and EQT can be used to rank
models without the need for any external source of evaluation data other than
lists of topics of interest. Moreover, our results reveal a disparity between
the models' ability to produce detailed explanations and their performance on
questions related to those explanations. This gap highlights fundamental
limitations in the internal knowledge representation and reasoning abilities of
current LLMs. We release the code at https://github.com/asgsaeid/EQT.
