---
layout: publication
title: 'Hallucination, Monofacts, And Miscalibration: An Empirical Investigation'
authors: Miranda Muqing Miao, Michael Kearns
conference: "Arxiv"
year: 2025
bibkey: miao2025empirical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.08666"}
tags: ['Transformer', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Pretraining Methods']
---
Hallucinated facts in large language models (LLMs) have recently been shown to obey a statistical lower bound determined by the monofact rate (related to the classical Good-Turing missing mass estimator) minus model miscalibration (Kalai & Vempala, 2024). We present the first empirical investigation of this three-way relationship in classical n-gram models and fine-tuned encoder-decoder Transformers. By generating training data from Pareto distributions with varying shape parameters, we systematically control the monofact rates and establish its positive relationship with hallucination. To bridge theory and practice, we derive an empirical analog of the hallucination bound by replacing the population miscalibration term (Section 2.1) with an empirical bin-wise KL divergence and confirm its practical viability. We then introduce selective upweighting -- a simple yet effective technique that strategically repeats as little as 5% of training examples -- to deliberately inject miscalibration into the model. This intervention reduces hallucination by up to 40%, challenging universal deduplication policies. Our experiments reveal a critical trade-off: selective upweighting maintains pre-injection levels of accuracy while substantially reducing hallucination, whereas standard training gradually improves accuracy but fails to address persistently high hallucination, indicating an inherent tension in optimization objectives.
