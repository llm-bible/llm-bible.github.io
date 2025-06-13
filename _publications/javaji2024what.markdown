---
layout: publication
title: 'What Would You Ask When You First Saw \(a^2+b^2=c^2\)? Evaluating LLM On Curiosity-driven Questioning'
authors: Shashidhar Reddy Javaji, Zining Zhu
conference: "Arxiv"
year: 2024
bibkey: javaji2024what
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.17172"}
tags: ['Tools', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Prompting']
---
Large language models (LLMs) can store a massive amount of knowledge, yet
their potential to acquire new knowledge remains unknown. We propose a novel
evaluation framework that evaluates this capability. This framework prompts
LLMs to generate questions about a statement introducing scientific knowledge,
simulating a curious person when facing the statement for the first time. We
score the qualities of the generated questions, thereby evaluating the
knowledge acquisition potential of the LLM. We apply controlled ablation
studies to validate our scoring procedures. Additionally, we created a
synthetic dataset consisting of 1101 statements in physics, chemistry, and
maths with distinct levels of difficulties, 300 general knowledge statements,
and 567 incorrect statements. Human evaluations were conducted to validate our
model assessments, achieving an approximate weighted Cohen's kappa of 0.7 on
all three metrics considered. We find that while large models like GPT-4 and
Mistral 8x7b are adept at generating coherent and relevant questions, the
smaller Phi-2 model is equally or more effective. This indicates that size does
not solely determine a model's knowledge acquisition potential. The proposed
framework quantifies a critical model capability that was commonly overlooked
and opens up research opportunities for developing more knowledgeable AI
systems
