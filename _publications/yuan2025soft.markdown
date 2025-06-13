---
layout: publication
title: 'Promptguard: Soft Prompt-guided Unsafe Content Moderation For Text-to-image Models'
authors: Lingzhi Yuan, Xiaojun Jia, Yihao Huang, Wei Dong, Yang Liu
conference: "Arxiv"
year: 2025
bibkey: yuan2025soft
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.03544"}
tags: ['Responsible AI', 'Efficiency and Optimization', 'Prompting', 'Reinforcement Learning']
---
Text-to-image (T2I) models have been shown to be vulnerable to misuse,
particularly in generating not-safe-for-work (NSFW) content, raising serious
ethical concerns. In this work, we present PromptGuard, a novel content
moderation technique that draws inspiration from the system prompt mechanism in
large language models (LLMs) for safety alignment. Unlike LLMs, T2I models lack
a direct interface for enforcing behavioral guidelines. Our key idea is to
optimize a safety soft prompt that functions as an implicit system prompt
within the T2I model's textual embedding space. This universal soft prompt (P*)
directly moderates NSFW inputs, enabling safe yet realistic image generation
without altering the inference efficiency or requiring proxy models. Extensive
experiments across three datasets demonstrate that PromptGuard effectively
mitigates NSFW content generation while preserving high-quality benign outputs.
PromptGuard achieves 7.8 times faster than prior content moderation methods,
surpassing eight state-of-the-art defenses with an optimal unsafe ratio down to
5.84%.
