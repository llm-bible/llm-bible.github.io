---
layout: publication
title: 'Is A Question Decomposition Unit All We Need?'
authors: Pruthvi Patel, Swaroop Mishra, Mihir Parmar, Chitta Baral
conference: "Arxiv"
year: 2022
bibkey: patel2022is
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2205.12538'}
  - {name: "Code", url: 'https://github.com/Pruthvi98/QuestionDecomposition'}
tags: ['GPT', 'Has Code', 'BERT', 'Model Architecture']
---
Large Language Models (LMs) have achieved state-of-the-art performance on
many Natural Language Processing (NLP) benchmarks. With the growing number of
new benchmarks, we build bigger and more complex LMs. However, building new LMs
may not be an ideal option owing to the cost, time and environmental impact
associated with it. We explore an alternative route: can we modify data by
expressing it in terms of the model's strengths, so that a question becomes
easier for models to answer? We investigate if humans can decompose a hard
question into a set of simpler questions that are relatively easier for models
to solve. We analyze a range of datasets involving various forms of reasoning
and find that it is indeed possible to significantly improve model performance
(24% for GPT3 and 29% for RoBERTa-SQuAD along with a symbolic calculator) via
decomposition. Our approach provides a viable option to involve people in NLP
research in a meaningful way. Our findings indicate that Human-in-the-loop
Question Decomposition (HQD) can potentially provide an alternate path to
building large LMs. Code and data is available at
https://github.com/Pruthvi98/QuestionDecomposition
