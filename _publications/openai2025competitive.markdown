---
layout: publication
title: 'Competitive Programming With Large Reasoning Models'
authors: Openai, :, Ahmed El-kishky, Alexander Wei, Andre Saraiva, Borys Minaiev, Daniel Selsam, David Dohan, Francis Song, Hunter Lightman, Ignasi Clavera, Jakub Pachocki, Jerry Tworek, Lorenz Kuhn, Lukasz Kaiser, Mark Chen, Max Schwarzer, Mostafa Rohaninejad, Nat Mcaleese, O3 Contributors, Oleg Mürk, Rhythm Garg, Rui Shu, Szymon Sidor, Vineet Kosaraju, Wenda Zhou
conference: "Arxiv"
year: 2025
bibkey: openai2025competitive
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.06807'}
tags: ['Reinforcement Learning', 'Agentic']
---
We show that reinforcement learning applied to large language models (LLMs)
significantly boosts performance on complex coding and reasoning tasks.
Additionally, we compare two general-purpose reasoning models - OpenAI o1 and
an early checkpoint of o3 - with a domain-specific system, o1-ioi, which uses
hand-engineered inference strategies designed for competing in the 2024
International Olympiad in Informatics (IOI). We competed live at IOI 2024 with
o1-ioi and, using hand-crafted test-time strategies, placed in the 49th
percentile. Under relaxed competition constraints, o1-ioi achieved a gold
medal. However, when evaluating later models such as o3, we find that o3
achieves gold without hand-crafted domain-specific strategies or relaxed
constraints. Our findings show that although specialized pipelines such as
o1-ioi yield solid improvements, the scaled-up, general-purpose o3 model
surpasses those results without relying on hand-crafted inference heuristics.
Notably, o3 achieves a gold medal at the 2024 IOI and obtains a Codeforces
rating on par with elite human competitors. Overall, these results indicate
that scaling general-purpose reinforcement learning, rather than relying on
domain-specific techniques, offers a robust path toward state-of-the-art AI in
reasoning domains, such as competitive programming.
