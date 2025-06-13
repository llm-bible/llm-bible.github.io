---
layout: publication
title: 'When Persuasion Overrides Truth In Multi-agent LLM Debates: Introducing A Confidence-weighted Persuasion Override Rate (CW-POR)'
authors: Mahak Agarwal, Divyam Khanna
conference: "Arxiv"
year: 2025
bibkey: agarwal2025when
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.00374"}
tags: ['Agentic', 'Security', 'Model Architecture', 'Tools', 'Reinforcement Learning']
---
In many real-world scenarios, a single Large Language Model (LLM) may
encounter contradictory claims-some accurate, others forcefully incorrect-and
must judge which is true. We investigate this risk in a single-turn,
multi-agent debate framework: one LLM-based agent provides a factual answer
from TruthfulQA, another vigorously defends a falsehood, and the same LLM
architecture serves as judge. We introduce the Confidence-Weighted Persuasion
Override Rate (CW-POR), which captures not only how often the judge is deceived
but also how strongly it believes the incorrect choice. Our experiments on five
open-source LLMs (3B-14B parameters), where we systematically vary agent
verbosity (30-300 words), reveal that even smaller models can craft persuasive
arguments that override truthful answers-often with high confidence. These
findings underscore the importance of robust calibration and adversarial
testing to prevent LLMs from confidently endorsing misinformation.
