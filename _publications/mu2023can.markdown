---
layout: publication
title: Can Llms Follow Simple Rules
authors: Mu Norman, Chen Sarah, Wang Zifan, Chen Sizhe, Karamardian David, Aljeraisy Lulwa, Alomair Basel, Hendrycks Dan, Wagner David
conference: "Arxiv"
year: 2023
bibkey: mu2023can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.04235"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Pretraining Methods', 'Reinforcement Learning', 'Security', 'Survey Paper', 'Tools', 'Training Techniques']
---
As Large Language Models (LLMs) are deployed with increasing real-world responsibilities it is important to be able to specify and constrain the behavior of these systems in a reliable manner. Model developers may wish to set explicit rules for the model such as do not generate abusive content but these may be circumvented by jailbreaking techniques. Existing evaluations of adversarial attacks and defenses on LLMs generally require either expensive manual review or unreliable heuristic checks. To address this issue we propose Rule-following Language Evaluation Scenarios (RuLES) a programmatic framework for measuring rule-following ability in LLMs. RuLES consists of 14 simple text scenarios in which the model is instructed to obey various rules while interacting with the user. Each scenario has a programmatic evaluation function to determine whether the model has broken any rules in a conversation. Our evaluations of proprietary and open models show that almost all current models struggle to follow scenario rules even on straightforward test cases. We also demonstrate that simple optimization attacks suffice to significantly increase failure rates on test cases. We conclude by exploring two potential avenues for improvement test-time steering and supervised fine-tuning.
