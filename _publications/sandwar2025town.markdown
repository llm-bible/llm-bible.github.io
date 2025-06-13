---
layout: publication
title: 'Town Hall Debate Prompting: Enhancing Logical Reasoning In Llms Through Multi-persona Interaction'
authors: Vivaan Sandwar, Bhav Jain, Rishan Thangaraj, Ishaan Garg, Michael Lam, Kevin Zhu
conference: "Arxiv"
year: 2025
bibkey: sandwar2025town
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.15725"}
tags: ['Prompting', 'Efficiency and Optimization', 'Model Architecture', 'GPT']
---
Debate is a commonly used form of human communication catered towards
problem-solving because of its efficiency. Debate fundamentally allows multiple
viewpoints to be brought up in problem-solving, and for complex problems, each
viewpoint opens a new path for problem-solving. In this work, we apply this
concept to LLM decision-making by proposing town hall-style debate prompting
(THDP), a prompting method that splices a language model into multiple personas
that will debate one another to reach a conclusion. Our experimental pipeline
varies both the number of personas and the personality types of each persona to
find the optimum town hall size and personality for benchmark performance as
measured by ZebraLogic bench, a reasoning-intensive benchmark characterized by
both multiple-choice and fill-in-the-blank questions. Our experimental results
demonstrate that a town hall size of 5 personas with LLM-determined personality
types performs optimally on ZebraLogic, achieving a 13% improvement over
one-shot CoT baselines in per-cell accuracy in GPT-4o, 9% puzzle accuracy
increase in Claude 3.5 Sonnet, and an improvement in hard puzzle accuracy from
10-15%.
