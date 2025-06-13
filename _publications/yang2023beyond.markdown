---
layout: publication
title: 'Beyond Testers'' Biases: Guiding Model Testing With Knowledge Bases Using Llms'
authors: Chenyang Yang, Rishabh Rustogi, Rachel Brower-sinning, Grace A. Lewis, Christian Kästner, Tongshuang Wu
conference: "Arxiv"
year: 2023
bibkey: yang2023beyond
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2310.09668'}
tags: ['RAG', 'GPT', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Ethics and Bias']
---
Current model testing work has mostly focused on creating test cases.
Identifying what to test is a step that is largely ignored and poorly
supported. We propose Weaver, an interactive tool that supports requirements
elicitation for guiding model testing. Weaver uses large language models to
generate knowledge bases and recommends concepts from them interactively,
allowing testers to elicit requirements for further testing. Weaver provides
rich external knowledge to testers and encourages testers to systematically
explore diverse concepts beyond their own biases. In a user study, we show that
both NLP experts and non-experts identified more, as well as more diverse
concepts worth testing when using Weaver. Collectively, they found more than
200 failing test cases for stance detection with zero-shot ChatGPT. Our case
studies further show that Weaver can help practitioners test models in
real-world settings, where developers define more nuanced application scenarios
(e.g., code understanding and transcript summarization) using LLMs.
