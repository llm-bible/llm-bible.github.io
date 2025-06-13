---
layout: publication
title: 'Assessing The Answerability Of Queries In Retrieval-augmented Code Generation'
authors: Geonmin Kim, Jaeyeon Kim, Hancheol Park, Wooksu Shin, Tae-ho Kim
conference: "Arxiv"
year: 2024
bibkey: kim2024assessing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.05547"}
tags: ['RAG', 'Tools', 'Applications']
---
Thanks to unprecedented language understanding and generation capabilities of
large language model (LLM), Retrieval-augmented Code Generation (RaCG) has
recently been widely utilized among software developers. While this has
increased productivity, there are still frequent instances of incorrect codes
being provided. In particular, there are cases where plausible yet incorrect
codes are generated for queries from users that cannot be answered with the
given queries and API descriptions. This study proposes a task for evaluating
answerability, which assesses whether valid answers can be generated based on
users' queries and retrieved APIs in RaCG. Additionally, we build a benchmark
dataset called Retrieval-augmented Code Generability Evaluation (RaCGEval) to
evaluate the performance of models performing this task. Experimental results
show that this task remains at a very challenging level, with baseline models
exhibiting a low performance of 46.7%. Furthermore, this study discusses
methods that could significantly improve performance.
