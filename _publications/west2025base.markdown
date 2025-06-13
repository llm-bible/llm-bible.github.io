---
layout: publication
title: 'Base Models Beat Aligned Models At Randomness And Creativity'
authors: Peter West, Christopher Potts
conference: "Arxiv"
year: 2025
bibkey: west2025base
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.00047'}
tags: ['Reinforcement Learning', 'Agentic']
---
Alignment has quickly become a default ingredient in LLM development, with
techniques such as reinforcement learning from human feedback making models act
safely, follow instructions, and perform ever-better on complex tasks. While
these techniques are certainly useful, we propose that they should not be
universally applied and demonstrate a range of tasks on which base language
models consistently outperform their popular aligned forms. Particularly, we
study tasks that require unpredictable outputs, such as random number
generation, mixed strategy games (rock-paper-scissors and hide-and-seek), and
creative writing. In each case, aligned models tend towards narrow behaviors
that result in distinct disadvantages, for instance, preferring to generate "7"
over other uniformly random numbers, becoming almost fully predictable in some
game states, or prioritizing pleasant writing over creative originality. Across
models tested, better performance on common benchmarks tends to correlate with
worse performance on our tasks, suggesting an effective trade-off in the
required capabilities.
