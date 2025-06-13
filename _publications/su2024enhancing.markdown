---
layout: publication
title: 'Enhancing Adversarial Attacks Through Chain Of Thought'
authors: Jingbo Su
conference: "Arxiv"
year: 2024
bibkey: su2024enhancing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.21791'}
  - {name: "Code", url: 'https://github.com/sujingbo0217/CS222W24-LLM-Attack'}
tags: ['Has Code', 'Security', 'Prompting', 'Reinforcement Learning', 'Responsible AI']
---
Large language models (LLMs) have demonstrated impressive performance across
various domains but remain susceptible to safety concerns. Prior research
indicates that gradient-based adversarial attacks are particularly effective
against aligned LLMs and the chain of thought (CoT) prompting can elicit
desired answers through step-by-step reasoning. This paper proposes enhancing
the robustness of adversarial attacks on aligned LLMs by integrating CoT
prompts with the greedy coordinate gradient (GCG) technique. Using CoT triggers
instead of affirmative targets stimulates the reasoning abilities of backend
LLMs, thereby improving the transferability and universality of adversarial
attacks. We conducted an ablation study comparing our CoT-GCG approach with
Amazon Web Services auto-cot. Results revealed our approach outperformed both
the baseline GCG attack and CoT prompting. Additionally, we used Llama Guard to
evaluate potentially harmful interactions, providing a more objective risk
assessment of entire conversations compared to matching outputs to rejection
phrases. The code of this paper is available at
https://github.com/sujingbo0217/CS222W24-LLM-Attack.
