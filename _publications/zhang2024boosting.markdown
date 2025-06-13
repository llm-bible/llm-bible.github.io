---
layout: publication
title: 'Boosting Jailbreak Attack With Momentum'
authors: Yihao Zhang, Zeming Wei
conference: "Arxiv"
year: 2024
bibkey: zhang2024boosting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.01229"}
  - {name: "Code", url: "https://github.com/weizeming/momentum-attack-llm"}
tags: ['Security', 'Efficiency and Optimization', 'Has Code', 'Prompting']
---
Large Language Models (LLMs) have achieved remarkable success across diverse
tasks, yet they remain vulnerable to adversarial attacks, notably the
well-known jailbreak attack. In particular, the Greedy Coordinate Gradient
(GCG) attack has demonstrated efficacy in exploiting this vulnerability by
optimizing adversarial prompts through a combination of gradient heuristics and
greedy search. However, the efficiency of this attack has become a bottleneck
in the attacking process. To mitigate this limitation, in this paper we rethink
the generation of the adversarial prompts through an optimization lens, aiming
to stabilize the optimization process and harness more heuristic insights from
previous optimization iterations. Specifically, we propose the
\textbf\{M\}omentum \textbf\{A\}ccelerated G\textbf\{C\}G (\textbf\{MAC\}) attack,
which integrates a momentum term into the gradient heuristic to boost and
stabilize the random search for tokens in adversarial prompts. Experimental
results showcase the notable enhancement achieved by MAC over baselines in
terms of attack success rate and optimization efficiency. Moreover, we
demonstrate that MAC can still exhibit superior performance for transfer
attacks and models under defense mechanisms. Our code is available at
https://github.com/weizeming/momentum-attack-llm.
