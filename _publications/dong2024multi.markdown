---
layout: publication
title: 'Promptexp: Multi-granularity Prompt Explanation Of Large Language Models'
authors: Ximing Dong, Shaowei Wang, Dayi Lin, Gopi Krishnan Rajbahadur, Boquan Zhou, Shichao Liu, Ahmed E. Hassan
conference: "Arxiv"
year: 2024
bibkey: dong2024multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.13073"}
tags: ['Tools', 'Applications', 'Interpretability and Explainability', 'RAG', 'Language Modeling', 'Reinforcement Learning', 'Masked Language Model', 'Prompting']
---
Large Language Models excel in tasks like natural language understanding and
text generation. Prompt engineering plays a critical role in leveraging LLM
effectively. However, LLMs black-box nature hinders its interpretability and
effective prompting engineering. A wide range of model explanation approaches
have been developed for deep learning models, However, these local explanations
are designed for single-output tasks like classification and regression,and
cannot be directly applied to LLMs, which generate sequences of tokens. Recent
efforts in LLM explanation focus on natural language explanations, but they are
prone to hallucinations and inaccuracies. To address this, we introduce
PromptExp , a framework for multi-granularity prompt explanations by
aggregating token-level insights. PromptExp introduces two token-level
explanation approaches: 1. an aggregation-based approach combining local
explanation techniques, and 2. a perturbation-based approach with novel
techniques to evaluate token masking impact. PromptExp supports both white-box
and black-box explanations and extends explanations to higher granularity
levels, enabling flexible analysis. We evaluate PromptExp in case studies such
as sentiment analysis, showing the perturbation-based approach performs best
using semantic similarity to assess perturbation impact. Furthermore, we
conducted a user study to confirm PromptExp's accuracy and practical value, and
demonstrate its potential to enhance LLM interpretability.
