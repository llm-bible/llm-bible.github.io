---
layout: publication
title: 'Measuring And Mitigating Constraint Violations Of In-context Learning For Utterance-to-api Semantic Parsing'
authors: Shufan Wang, Sebastien Jean, Sailik Sengupta, James Gung, Nikolaos Pappas, Yi Zhang
conference: "Arxiv"
year: 2023
bibkey: wang2023measuring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.15338"}
tags: ['Tools', 'RAG', 'Training Techniques', 'Prompting', 'In-Context Learning']
---
In executable task-oriented semantic parsing, the system aims to translate
users' utterances in natural language to machine-interpretable programs (API
calls) that can be executed according to pre-defined API specifications. With
the popularity of Large Language Models (LLMs), in-context learning offers a
strong baseline for such scenarios, especially in data-limited regimes.
However, LLMs are known to hallucinate and therefore pose a formidable
challenge in constraining generated content. Thus, it remains uncertain if LLMs
can effectively perform task-oriented utterance-to-API generation where
respecting API's structural and task-specific constraints is crucial.
  In this work, we seek to measure, analyze and mitigate such constraints
violations. First, we identify the categories of various constraints in
obtaining API-semantics from task-oriented utterances, and define fine-grained
metrics that complement traditional ones. Second, we leverage these metrics to
conduct a detailed error analysis of constraints violations seen in
state-of-the-art LLMs, which motivates us to investigate two mitigation
strategies: Semantic-Retrieval of Demonstrations (SRD) and API-aware
Constrained Decoding (API-CD). Our experiments show that these strategies are
effective at reducing constraints violations and improving the quality of the
generated API calls, but require careful consideration given their
implementation complexity and latency.
