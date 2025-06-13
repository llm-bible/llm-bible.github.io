---
layout: publication
title: 'Zebralogic: On The Scaling Limits Of Llms For Logical Reasoning'
authors: Bill Yuchen Lin, Ronan Le Bras, Kyle Richardson, Ashish Sabharwal, Radha Poovendran, Peter Clark, Yejin Choi
conference: "Arxiv"
year: 2025
bibkey: lin2025scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.01100"}
tags: ['Prompting', 'Tools']
---
We investigate the logical reasoning capabilities of large language models
(LLMs) and their scalability in complex non-monotonic reasoning. To this end,
we introduce ZebraLogic, a comprehensive evaluation framework for assessing LLM
reasoning performance on logic grid puzzles derived from constraint
satisfaction problems (CSPs). ZebraLogic enables the generation of puzzles with
controllable and quantifiable complexity, facilitating a systematic study of
the scaling limits of models such as Llama, o1 models, and DeepSeek-R1. By
encompassing a broad range of search space complexities and diverse logical
constraints, ZebraLogic provides a structured environment to evaluate reasoning
under increasing difficulty.
  Our results reveal a significant decline in accuracy as problem complexity
grows -- a phenomenon we term the curse of complexity. This limitation persists
even with larger models and increased inference-time computation, suggesting
inherent constraints in current LLM reasoning capabilities. Additionally, we
explore strategies to enhance logical reasoning, including Best-of-N sampling,
backtracking mechanisms, and self-verification prompts. Our findings offer
critical insights into the scalability of LLM reasoning, highlight fundamental
limitations, and outline potential directions for improvement.
