---
layout: publication
title: 'Benchmarking And Explaining Large Language Model-based Code Generation: A Causality-centric Approach'
authors: Ji Zhenlan, Ma Pingchuan, Li Zongjie, Wang Shuai
conference: "Arxiv"
year: 2023
bibkey: ji2023benchmarking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.06680"}
tags: ['Applications', 'Ethics And Bias', 'Prompting', 'Reinforcement Learning', 'Tools']
---
While code generation has been widely used in various software development
scenarios, the quality of the generated code is not guaranteed. This has been a
particular concern in the era of large language models (LLMs)- based code
generation, where LLMs, deemed a complex and powerful black-box model, is
instructed by a high-level natural language specification, namely a prompt, to
generate code. Nevertheless, effectively evaluating and explaining the code
generation capability of LLMs is inherently challenging, given the complexity
of LLMs and the lack of transparency.
  Inspired by the recent progress in causality analysis and its application in
software engineering, this paper launches a causality analysis-based approach
to systematically analyze the causal relations between the LLM input prompts
and the generated code. To handle various technical challenges in this study,
we first propose a novel causal graph-based representation of the prompt and
the generated code, which is established over the fine-grained,
human-understandable concepts in the input prompts. The formed causal graph is
then used to identify the causal relations between the prompt and the derived
code. We illustrate the insights that our framework can provide by studying
over 3 popular LLMs with over 12 prompt adjustment strategies. The results of
these studies illustrate the potential of our technique to provide insights
into LLM effectiveness, and aid end-users in understanding predictions.
Additionally, we demonstrate that our approach provides actionable insights to
improve the quality of the LLM-generated code by properly calibrating the
prompt.
