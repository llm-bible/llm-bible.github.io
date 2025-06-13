---
layout: publication
title: 'HREF: Human Response-guided Evaluation Of Instruction Following In Language Models'
authors: Xinxi Lyu, Yizhong Wang, Hannaneh Hajishirzi, Pradeep Dasigi
conference: "Arxiv"
year: 2024
bibkey: lyu2024human
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.15524"}
tags: ['Prompting', 'Ethics and Bias', 'RAG']
---
Evaluating the capability of Large Language Models (LLMs) in following
instructions has heavily relied on a powerful LLM as the judge, introducing
unresolved biases that deviate the judgments from human judges. In this work,
we reevaluate various choices for automatic evaluation on a wide range of
instruction-following tasks. We experiment with methods that leverage
human-written responses and observe that they enhance the reliability of
automatic evaluations across a wide range of tasks, resulting in up to a 3.2%
improvement in agreement with human judges. We also discovered that
human-written responses offer an orthogonal perspective to model-generated
responses in following instructions and should be used as an additional context
when comparing model responses. Based on these observations, we develop a new
evaluation benchmark, Human Response-Guided Evaluation of Instruction Following
(HREF), comprising 4,258 samples across 11 task categories with a composite
evaluation setup, employing a composite evaluation setup that selects the most
reliable method for each category. In addition to providing reliable
evaluation, HREF emphasizes individual task performance and is free from
contamination. Finally, we study the impact of key design choices in HREF,
including the size of the evaluation set, the judge model, the baseline model,
and the prompt template. We host a live leaderboard that evaluates LLMs on the
private evaluation set of HREF.
