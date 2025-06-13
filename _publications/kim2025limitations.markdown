---
layout: publication
title: 'Limitations Of Large Language Models In Clinical Problem-solving Arising From Inflexible Reasoning'
authors: Jonathan Kim, Anna Podlasek, Kie Shidara, Feng Liu, Ahmed Alaa, Danilo Bernardo
conference: "Arxiv"
year: 2025
bibkey: kim2025limitations
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.04381"}
tags: ['Ethics and Bias', 'Security', 'Training Techniques', 'Reinforcement Learning']
---
Large Language Models (LLMs) have attained human-level accuracy on medical
question-answer (QA) benchmarks. However, their limitations in navigating
open-ended clinical scenarios have recently been shown, raising concerns about
the robustness and generalizability of LLM reasoning across diverse, real-world
medical tasks. To probe potential LLM failure modes in clinical
problem-solving, we present the medical abstraction and reasoning corpus
(M-ARC). M-ARC assesses clinical reasoning through scenarios designed to
exploit the Einstellung effect -- the fixation of thought arising from prior
experience, targeting LLM inductive biases toward inflexible pattern matching
from their training data rather than engaging in flexible reasoning. We find
that LLMs, including current state-of-the-art o1 and Gemini models, perform
poorly compared to physicians on M-ARC, often demonstrating lack of commonsense
medical reasoning and a propensity to hallucinate. In addition, uncertainty
estimation analyses indicate that LLMs exhibit overconfidence in their answers,
despite their limited accuracy. The failure modes revealed by M-ARC in LLM
medical reasoning underscore the need to exercise caution when deploying these
models in clinical settings.
