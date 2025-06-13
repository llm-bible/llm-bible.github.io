---
layout: publication
title: 'Interpretable Llm-based Table Question Answering'
authors: Giang Nguyen, Ivan Brugere, Shubham Sharma, Sanjay Kariyappa, Anh Totti Nguyen, Freddy Lecue
conference: "Arxiv"
year: 2024
bibkey: nguyen2024interpretable
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.12386'}
tags: ['Reinforcement Learning', 'Interpretability and Explainability', 'Efficiency and Optimization', 'Applications']
---
Interpretability for Table Question Answering (Table QA) is critical,
particularly in high-stakes industries like finance or healthcare. Although
recent approaches using Large Language Models (LLMs) have significantly
improved Table QA performance, their explanations for how the answers are
generated are ambiguous. To fill this gap, we introduce Plan-of-SQLs (POS), an
interpretable Table QA approach designed to improve users' understanding of
model decision-making. Through qualitative and quantitative evaluations with
human and LLM judges, we show that: First, POS is the highest-quality
explanation method, helps human users understand model behaviors, and
facilitates model prediction verification. Second, when evaluated on popular
and standard Table QA datasets (TabFact, WikiTQ, and FetaQA), POS achieves QA
accuracy that is competitive with or superior to existing methods, while also
offering greater efficiency-requiring significantly fewer LLM calls and table
database queries-and robust performance on large-sized tables. Finally, we
observe high agreement (up to 90%) between LLMs and human users when making
decisions based on the same explanations, suggesting that LLMs could serve as
an effective proxy for humans in evaluating explanations. This finding enables
faster, more affordable evaluation of AI explanations-possibly accelerating
trustworthy AI research while maintaining reliable judgments on
interpretability.
