---
layout: publication
title: "Fight Back Against Jailbreaking Via Prompt Adversarial Tuning"
authors: Mo Yichuan, Wang Yuji, Wei Zeming, Wang Yisen
conference: "Arxiv"
year: 2024
bibkey: mo2024fight
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.06255"}
  - {name: "Code", url: "https://github.com/rain152/PAT"}
tags: ['Applications', 'Fine Tuning', 'Has Code', 'Prompting', 'Reinforcement Learning', 'Security', 'Training Techniques']
---
While Large Language Models (LLMs) have achieved tremendous success in various applications they are also susceptible to jailbreak attacks. Several primary defense strategies have been proposed to protect LLMs from producing harmful information mostly with a particular focus on harmful content filtering or heuristical defensive prompt designs. However how to achieve intrinsic robustness through the prompts remains an open problem. In this paper motivated by adversarial training paradigms for achieving reliable robustness we propose an approach named Prompt Adversarial Tuning (PAT) that trains a prompt control attached to the user prompt as a guard prefix. To achieve our defense goal whilst maintaining natural performance we optimize the control prompt with both adversarial and benign prompts. Comprehensive experiments show that our method is effective against both grey-box and black-box attacks reducing the success rate of advanced attacks to nearly 0 while maintaining the models utility on the benign task. The proposed defense strategy incurs only negligible computational overhead charting a new perspective for future explorations in LLM security. Our code is available at https://github.com/rain152/PAT."
