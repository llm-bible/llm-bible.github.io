---
layout: publication
title: Boosting Jailbreak Attack With Momentum
authors: Zhang Yihao, Wei Zeming
conference: "Arxiv"
year: 2024
bibkey: zhang2024boosting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.01229"}
  - {name: "Code", url: "https://github.com/weizeming/momentum&#45;attack&#45;llm"}
tags: ['Applications', 'Efficiency And Optimization', 'Has Code', 'Prompting', 'Security']
---
Large Language Models (LLMs) have achieved remarkable success across diverse tasks yet they remain vulnerable to adversarial attacks notably the well45;documented textit123;jailbreak125; attack. Recently the Greedy Coordinate Gradient (GCG) attack has demonstrated efficacy in exploiting this vulnerability by optimizing adversarial prompts through a combination of gradient heuristics and greedy search. However the efficiency of this attack has become a bottleneck in the attacking process. To mitigate this limitation in this paper we rethink the generation of adversarial prompts through an optimization lens aiming to stabilize the optimization process and harness more heuristic insights from previous iterations. Specifically we introduce the textbf123;M125;omentum textbf123;A125;ccelerated Gtextbf123;C125;G (textbf123;MAC125;) attack which incorporates a momentum term into the gradient heuristic. Experimental results showcase the notable enhancement achieved by MAP in gradient45;based attacks on aligned language models. Our code is available at https://github.com/weizeming/momentum&#45;attack&#45;llm.
