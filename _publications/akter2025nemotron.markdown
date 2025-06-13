---
layout: publication
title: 'Nemotron-crossthink: Scaling Self-learning Beyond Math Reasoning'
authors: Syeda Nahida Akter, Shrimai Prabhumoye, Matvei Novikov, Seungju Han, Ying Lin, Evelina Bakhturina, Eric Nyberg, Yejin Choi, Mostofa Patwary, Mohammad Shoeybi, Bryan Catanzaro
conference: "Arxiv"
year: 2025
bibkey: akter2025nemotron
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.13941'}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning']
---
Large Language Models (LLMs) have shown strong reasoning capabilities,
particularly when enhanced through Reinforcement Learning (RL). While prior
work has successfully applied RL to mathematical reasoning -- where rules and
correctness are well-defined -- generalizing these methods to broader reasoning
domains remains challenging due to limited data, the lack of verifiable reward
structures, and diverse task requirements. In this work, we propose
NEMOTRON-CROSSTHINK, a framework that systematically incorporates multi-domain
corpora, including both synthetic and real-world question-answer pairs, into RL
training to improve generalization across diverse reasoning tasks.
NEMOTRON-CROSSTHINK addresses key challenges by (1) incorporating data from
varied sources spanning STEM, humanities, social sciences, etc.; (2) applying
structured templates (e.g., multiple-choice and open-ended) to control
answer-space complexity; (3) filtering for verifiable answers; and (4)
optimizing data blending strategies that utilizes data from multiple sources
effectively. Our approach enables scalable and verifiable reward modeling
beyond mathematics and demonstrates improved accuracies on both math (MATH-500:
+30.1%, AMC23:+27.5%) and non-math reasoning benchmarks (MMLU-PRO: +12.8%,
GPQA-DIAMOND: +11.3%, AGIEVAL: +15.1%, SUPERGPQA: +3.8%). Moreover,
NEMOTRON-CROSSTHINK exhibits significantly improved response efficiency --
using 28% fewer tokens for correct answers -- highlighting more focused and
effective reasoning. Through NEMOTRON-CROSSTHINK, we demonstrate that
integrating multi-domain, multi-format data in RL leads to more accurate,
efficient, and generalizable LLMs.
