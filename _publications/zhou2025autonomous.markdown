---
layout: publication
title: 'Tempest: Autonomous Multi-turn Jailbreaking Of Large Language Models With Tree Search'
authors: Andy Zhou, Ron Arel
conference: "Arxiv"
year: 2025
bibkey: zhou2025autonomous
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.10619"}
tags: ['Responsible AI', 'Security', 'Model Architecture', 'Tools', 'GPT', 'Prompting']
---
We introduce Tempest, a multi-turn adversarial framework that models the gradual erosion of Large Language Model (LLM) safety through a tree search perspective. Unlike single-turn jailbreaks that rely on one meticulously engineered prompt, Tempest expands the conversation at each turn in a breadth-first fashion, branching out multiple adversarial prompts that exploit partial compliance from previous responses. By tracking these incremental policy leaks and re-injecting them into subsequent queries, Tempest reveals how minor concessions can accumulate into fully disallowed outputs. Evaluations on the JailbreakBench dataset show that Tempest achieves a 100% success rate on GPT-3.5-turbo and 97% on GPT-4 in a single multi-turn run, using fewer queries than baselines such as Crescendo or GOAT. This tree search methodology offers an in-depth view of how model safeguards degrade over successive dialogue turns, underscoring the urgency of robust multi-turn testing procedures for language models.
