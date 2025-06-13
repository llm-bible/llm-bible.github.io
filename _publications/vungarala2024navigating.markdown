---
layout: publication
title: 'Spicepilot: Navigating SPICE Code Generation And Simulation With AI Guidance'
authors: Deepak Vungarala, Sakila Alam, Arnob Ghosh, Shaahin Angizi
conference: "Arxiv"
year: 2024
bibkey: vungarala2024navigating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.20553'}
  - {name: "Code", url: 'https://github.com/ACADLab/SPICEPilot.git'}
tags: ['Has Code', 'Applications', 'Tools']
---
Large Language Models (LLMs) have shown great potential in automating code
generation; however, their ability to generate accurate circuit-level SPICE
code remains limited due to a lack of hardware-specific knowledge. In this
paper, we analyze and identify the typical limitations of existing LLMs in
SPICE code generation. To address these limitations, we present SPICEPilot a
novel Python-based dataset generated using PySpice, along with its accompanying
framework. This marks a significant step forward in automating SPICE code
generation across various circuit configurations. Our framework automates the
creation of SPICE simulation scripts, introduces standardized benchmarking
metrics to evaluate LLM's ability for circuit generation, and outlines a
roadmap for integrating LLMs into the hardware design process. SPICEPilot is
open-sourced under the permissive MIT license at
https://github.com/ACADLab/SPICEPilot.git.
