---
layout: publication
title: 'Large Language Models To Generate System-level Test Programs Targeting Non-functional Properties'
authors: Schwachhofer Denis, Domanski Peter, Becker Steffen, Wagner Stefan, Sauer Matthias, Pflüger Dirk, Polian Ilia
conference: "Arxiv"
year: 2024
bibkey: schwachhofer2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.10086"}
tags: ['Efficiency And Optimization', 'Model Architecture', 'Prompting', 'Training Techniques']
---
System-Level Test (SLT) has been a part of the test flow for integrated circuits for over a decade and still gains importance. However, no systematic approaches exist for test program generation, especially targeting non-functional properties of the Device under Test (DUT). Currently, test engineers manually compose test suites from off-the-shelf software, approximating the end-user environment of the DUT. This is a challenging and tedious task that does not guarantee sufficient control over non-functional properties. This paper proposes Large Language Models (LLMs) to generate test programs. We take a first glance at how pre-trained LLMs perform in test program generation to optimize non-functional properties of the DUT. Therefore, we write a prompt to generate C code snippets that maximize the instructions per cycle of a super-scalar, out-of-order architecture in simulation. Additionally, we apply prompt and hyperparameter optimization to achieve the best possible results without further training.
