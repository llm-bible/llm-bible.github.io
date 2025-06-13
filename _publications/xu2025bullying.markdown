---
layout: publication
title: 'Bullying The Machine: How Personas Increase LLM Vulnerability'
authors: Ziwei Xu, Udit Sanghi, Mohan Kankanhalli
conference: "Arxiv"
year: 2025
bibkey: xu2025bullying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.12692"}
tags: ['Responsible AI', 'Tools', 'Reinforcement Learning', 'Security', 'Prompting']
---
Large Language Models (LLMs) are increasingly deployed in interactions where they are prompted to adopt personas. This paper investigates whether such persona conditioning affects model safety under bullying, an adversarial manipulation that applies psychological pressures in order to force the victim to comply to the attacker. We introduce a simulation framework in which an attacker LLM engages a victim LLM using psychologically grounded bullying tactics, while the victim adopts personas aligned with the Big Five personality traits. Experiments using multiple open-source LLMs and a wide range of adversarial goals reveal that certain persona configurations -- such as weakened agreeableness or conscientiousness -- significantly increase victim's susceptibility to unsafe outputs. Bullying tactics involving emotional or sarcastic manipulation, such as gaslighting and ridicule, are particularly effective. These findings suggest that persona-driven interaction introduces a novel vector for safety risks in LLMs and highlight the need for persona-aware safety evaluation and alignment strategies.
