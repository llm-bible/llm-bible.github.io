---
layout: publication
title: 'Metallm: A High-performant And Cost-efficient Dynamic Framework For Wrapping Llms'
authors: Quang H. Nguyen, Thinh Dao, Duy C. Hoang, Juliette Decugis, Saurav Manchanda, Nitesh V. Chawla, Khoa D. Doan
conference: "Arxiv"
year: 2024
bibkey: nguyen2024high
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.10834"}
tags: ['Efficiency and Optimization', 'RAG', 'Tools', 'Reinforcement Learning']
---
The rapid progress in machine learning (ML) has brought forth many large
language models (LLMs) that excel in various tasks and areas. These LLMs come
with different abilities and costs in terms of computation or pricing. Since
the demand for each query can vary, e.g., because of the queried domain or its
complexity, defaulting to one LLM in an application is not usually the best
choice, whether it is the biggest, priciest, or even the one with the best
average test performance. Consequently, picking the right LLM that is both
accurate and cost-effective for an application is necessary yet remains a
challenge. In this paper, we introduce MetaLLM, a framework that dynamically
and intelligently routes each query to the optimal LLM (among several available
LLMs) for classification and multi-choice question-answering tasks, achieving
significantly improved accuracy and cost-effectiveness. By framing the
selection problem as a multi-armed bandit, MetaLLM balances prediction accuracy
and cost efficiency under uncertainty. Our experiments, conducted on popular
LLM platforms such as OpenAI and Together AI, as well as open-source LLM,
showcase MetaLLM's efficacy in real-world scenarios, laying the groundwork for
future extensions.
