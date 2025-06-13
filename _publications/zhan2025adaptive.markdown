---
layout: publication
title: 'Adaptive Attacks Break Defenses Against Indirect Prompt Injection Attacks On LLM Agents'
authors: Qiusi Zhan, Richard Fang, Henil Shalin Panchal, Daniel Kang
conference: "Arxiv"
year: 2025
bibkey: zhan2025adaptive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.00061"}
  - {name: "Code", url: "https://github.com/uiuc-kang-lab/AdaptiveAttackAgent"}
tags: ['Agentic', 'Security', 'Tools', 'Has Code', 'Prompting', 'Applications']
---
Large Language Model (LLM) agents exhibit remarkable performance across
diverse applications by using external tools to interact with environments.
However, integrating external tools introduces security risks, such as indirect
prompt injection (IPI) attacks. Despite defenses designed for IPI attacks,
their robustness remains questionable due to insufficient testing against
adaptive attacks. In this paper, we evaluate eight different defenses and
bypass all of them using adaptive attacks, consistently achieving an attack
success rate of over 50%. This reveals critical vulnerabilities in current
defenses. Our research underscores the need for adaptive attack evaluation when
designing defenses to ensure robustness and reliability. The code is available
at https://github.com/uiuc-kang-lab/AdaptiveAttackAgent.
