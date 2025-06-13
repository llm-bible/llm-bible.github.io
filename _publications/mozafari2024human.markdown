---
layout: publication
title: 'Wikihint: A Human-annotated Dataset For Hint Ranking And Generation'
authors: Jamshid Mozafari, Florian Gerhold, Adam Jatowt
conference: "Proceedings of the 48th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2025)"
year: 2024
bibkey: mozafari2024human
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.01626'}
tags: ['Uncategorized']
---
The use of Large Language Models (LLMs) has increased significantly with
users frequently asking questions to chatbots. In the time when information is
readily accessible, it is crucial to stimulate and preserve human cognitive
abilities and maintain strong reasoning skills. This paper addresses such
challenges by promoting the use of hints as an alternative or a supplement to
direct answers. We first introduce a manually constructed hint dataset,
WikiHint, which is based on Wikipedia and includes 5,000 hints created for
1,000 questions. We then finetune open-source LLMs for hint generation in
answer-aware and answer-agnostic contexts. We assess the effectiveness of the
hints with human participants who answer questions with and without the aid of
hints. Additionally, we introduce a lightweight evaluation method, HintRank, to
evaluate and rank hints in both answer-aware and answer-agnostic settings. Our
findings show that (a) the dataset helps generate more effective hints, (b)
including answer information along with questions generally improves the
quality of generated hints, and (c) encoder-based models perform better than
decoder-based models in hint ranking.
