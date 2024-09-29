---
layout: publication
title: Verifiably Following Complex Robot Instructions With Foundation Models
authors: Quartey Benedict, Rosen Eric, Tellex Stefanie, Konidaris George
conference: "Arxiv"
year: 2024
bibkey: quartey2024verifiably
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11498"}
  - {name: "Code", url: "https://robotlimp.github.io"}
tags: ['Has Code', 'Model Architecture', 'Reinforcement Learning']
---
Enabling mobile robots to follow complex natural language instructions is an important yet challenging problem. People want to flexibly express constraints refer to arbitrary landmarks and verify behavior when instructing robots. Conversely robots must disambiguate human instructions into specifications and ground instruction referents in the real world. We propose Language Instruction grounding for Motion Planning (LIMP) an approach that enables robots to verifiably follow expressive and complex open45;ended instructions in real45;world environments without prebuilt semantic maps. LIMP constructs a symbolic instruction representation that reveals the robots alignment with an instructors intended motives and affords the synthesis of robot behaviors that are correct45;by45;construction. We perform a large scale evaluation and demonstrate our approach on 150 instructions in five real45;world environments showing the generality of our approach and the ease of deployment in novel unstructured domains. In our experiments LIMP performs comparably with state45;of45;the45;art LLM task planners and LLM code45;writing planners on standard open vocabulary tasks and additionally achieves 7937; success rate on complex spatiotemporal instructions while LLM and Code45;writing planners both achieve 3837;. See supplementary materials and demo videos at https://robotlimp.github.io
