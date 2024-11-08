---
layout: publication
title: 'Boosting Jailbreak Attack With Momentum'
authors: Zhang Yihao, Wei Zeming
conference: "Arxiv"
year: 2024
bibkey: zhang2024boosting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.01229"}
  - {name: "Code", url: "https://github.com/weizeming/momentum-attack-llm"}
tags: ['Efficiency And Optimization', 'Has Code', 'Prompting', 'Security']
---
Large Language Models (LLMs) have achieved remarkable success across diverse
tasks, yet they remain vulnerable to adversarial attacks, notably the
well-documented \textit\{jailbreak\} attack. Recently, the Greedy Coordinate
Gradient (GCG) attack has demonstrated efficacy in exploiting this
vulnerability by optimizing adversarial prompts through a combination of
gradient heuristics and greedy search. However, the efficiency of this attack
has become a bottleneck in the attacking process. To mitigate this limitation,
in this paper we rethink the generation of adversarial prompts through an
optimization lens, aiming to stabilize the optimization process and harness
more heuristic insights from previous iterations. Specifically, we introduce
the \textbf\{M\}omentum \textbf\{A\}ccelerated G\textbf\{C\}G (\textbf\{MAC\}) attack,
which incorporates a momentum term into the gradient heuristic. Experimental
results showcase the notable enhancement achieved by MAP in gradient-based
attacks on aligned language models. Our code is available at
https://github.com/weizeming/momentum-attack-llm.
