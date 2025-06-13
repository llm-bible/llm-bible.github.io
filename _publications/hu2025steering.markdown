---
layout: publication
title: 'Steering Dialogue Dynamics For Robustness Against Multi-turn Jailbreaking Attacks'
authors: Hanjiang Hu, Alexander Robey, Changliu Liu
conference: "Arxiv"
year: 2025
bibkey: hu2025steering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.00187"}
  - {name: "Code", url: "https://github.com/HanjiangHu/NBF-LLM"}
tags: ['Responsible AI', 'Tools', 'Merging', 'Security', 'Has Code', 'Prompting']
---
Large language models (LLMs) are highly vulnerable to jailbreaking attacks,
wherein adversarial prompts are designed to elicit harmful responses. While
existing defenses effectively mitigate single-turn attacks by detecting and
filtering unsafe inputs, they fail against multi-turn jailbreaks that exploit
contextual drift over multiple interactions, gradually leading LLMs away from
safe behavior. To address this challenge, we propose a safety steering
framework grounded in safe control theory, ensuring invariant safety in
multi-turn dialogues. Our approach models the dialogue with LLMs using
state-space representations and introduces a novel neural barrier function
(NBF) to detect and filter harmful queries emerging from evolving contexts
proactively. Our method achieves invariant safety at each turn of dialogue by
learning a safety predictor that accounts for adversarial queries, preventing
potential context drift toward jailbreaks. Extensive experiments under multiple
LLMs show that our NBF-based safety steering outperforms safety alignment
baselines, offering stronger defenses against multi-turn jailbreaks while
maintaining a better trade-off between safety and helpfulness under different
multi-turn jailbreak methods. Our code is available at
https://github.com/HanjiangHu/NBF-LLM .
