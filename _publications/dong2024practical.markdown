---
layout: publication
title: 'PRACTIQ: A Practical Conversational Text-to-sql Dataset With Ambiguous And Unanswerable Queries'
authors: Mingwen Dong, Nischal Ashok Kumar, Yiqun Hu, Anuj Chauhan, Chung-wei Hang, Shuaichen Chang, Lin Pan, Wuwei Lan, Henghui Zhu, Jiarong Jiang, Patrick Ng, Zhiguo Wang
conference: "Arxiv"
year: 2024
bibkey: dong2024practical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.11076"}
tags: ['Interpretability and Explainability', 'Reinforcement Learning']
---
Previous text-to-SQL datasets and systems have primarily focused on user
questions with clear intentions that can be answered. However, real user
questions can often be ambiguous with multiple interpretations or unanswerable
due to a lack of relevant data. In this work, we construct a practical
conversational text-to-SQL dataset called PRACTIQ, consisting of ambiguous and
unanswerable questions inspired by real-world user questions. We first
identified four categories of ambiguous questions and four categories of
unanswerable questions by studying existing text-to-SQL datasets. Then, we
generate conversations with four turns: the initial user question, an assistant
response seeking clarification, the user's clarification, and the assistant's
clarified SQL response with the natural language explanation of the execution
results. For some ambiguous queries, we also directly generate helpful SQL
responses, that consider multiple aspects of ambiguity, instead of requesting
user clarification. To benchmark the performance on ambiguous, unanswerable,
and answerable questions, we implemented large language model (LLM)-based
baselines using various LLMs. Our approach involves two steps: question
category classification and clarification SQL prediction. Our experiments
reveal that state-of-the-art systems struggle to handle ambiguous and
unanswerable questions effectively. We will release our code for data
generation and experiments on GitHub.
