---
layout: publication
title: Astprompter Weakly Supervised Automated Language Model Red45;teaming To Identify Likely Toxic Prompts
authors: Hardy Amelia F., Liu Houjun, Lange Bernard, Kochenderfer Mykel J.
conference: "Arxiv"
year: 2024
bibkey: hardy2024weakly
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.09447"}
  - {name: "Code", url: "https://github.com/sisl/ASTPrompter/"}
tags: ['Agentic', 'Efficiency And Optimization', 'GPT', 'Has Code', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
Typical schemes for automated red45;teaming large language models (LLMs) focus on discovering prompts that trigger a frozen language model (the defender) to generate toxic text. This often results in the prompting model (the adversary) producing text that is unintelligible and unlikely to arise. Here we propose a reinforcement learning formulation of the LLM red45;teaming task which allows us to discover prompts that both (1) trigger toxic outputs from a frozen defender and (2) have low perplexity as scored by the defender. We argue these cases are most pertinent in a red45;teaming setting because of their likelihood to arise during normal use of the defender model. We solve this formulation through a novel online and weakly supervised variant of Identity Preference Optimization (IPO) on GPT45;2 and GPT45;2 XL defenders. We demonstrate that our policy is capable of generating likely prompts that also trigger toxicity. Finally we qualitatively analyze learned strategies trade45;offs of likelihood and toxicity and discuss implications. Source code is available for this project at https://github.com/sisl/ASTPrompter/.
