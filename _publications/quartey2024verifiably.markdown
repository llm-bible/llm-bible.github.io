---
layout: publication
title: 'Verifiably Following Complex Robot Instructions With Foundation Models'
authors: Quartey Benedict, Rosen Eric, Tellex Stefanie, Konidaris George
conference: "Arxiv"
year: 2024
bibkey: quartey2024verifiably
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11498"}
  - {name: "Code", url: "https://robotlimp.github.io"}
tags: ['Ethics And Bias', 'Has Code', 'Reinforcement Learning']
---
Enabling mobile robots to follow complex natural language instructions is an important yet challenging problem. People want to flexibly express constraints, refer to arbitrary landmarks and verify behavior when instructing robots. Conversely, robots must disambiguate human instructions into specifications and ground instruction referents in the real world. We propose Language Instruction grounding for Motion Planning (LIMP), an approach that enables robots to verifiably follow expressive and complex open-ended instructions in real-world environments without prebuilt semantic maps. LIMP constructs a symbolic instruction representation that reveals the robot's alignment with an instructor's intended motives and affords the synthesis of robot behaviors that are correct-by-construction. We perform a large scale evaluation and demonstrate our approach on 150 instructions in five real-world environments showing the generality of our approach and the ease of deployment in novel unstructured domains. In our experiments, LIMP performs comparably with state-of-the-art LLM task planners and LLM code-writing planners on standard open vocabulary tasks and additionally achieves 79\&#37; success rate on complex spatiotemporal instructions while LLM and Code-writing planners both achieve 38\&#37;. See supplementary materials and demo videos at https://robotlimp.github.io
