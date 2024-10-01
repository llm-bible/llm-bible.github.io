---
layout: publication
title: 'Exploring The Compositional Deficiency Of Large Language Models In Mathematical Reasoning'
authors: Zhao Jun, Tong Jingqi, Mou Yurong, Zhang Ming, Zhang Qi, Huang Xuanjing
conference: "Arxiv"
year: 2024
bibkey: zhao2024exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.06680"}
tags: ['Few Shot', 'Fine Tuning', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Human cognition exhibits systematic compositionality, the algebraic ability to generate infinite novel combinations from finite learned components, which is the key to understanding and reasoning about complex logic. In this work, we investigate the compositionality of large language models (LLMs) in mathematical reasoning. Specifically, we construct a new dataset \textsc\{MathTrap\}\footnotemark[3] by introducing carefully designed logical traps into the problem descriptions of MATH and GSM8k. Since problems with logical flaws are quite rare in the real world, these represent unseen'' cases to LLMs. Solving these requires the models to systematically compose (1) the mathematical knowledge involved in the original problems with (2) knowledge related to the introduced traps. Our experiments show that while LLMs possess both components of requisite knowledge, they do not \textbf\{spontaneously\} combine them to handle these novel cases. We explore several methods to mitigate this deficiency, such as natural language prompts, few-shot demonstrations, and fine-tuning. We find that LLMs' performance can be \textbf\{passively\} improved through the above external intervention. Overall, systematic compositionality remains an open challenge for large language models.
