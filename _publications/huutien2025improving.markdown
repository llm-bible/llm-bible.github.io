---
layout: publication
title: 'Improving LLM Unlearning Robustness Via Random Perturbations'
authors: Dang Huu-tien, Hoang Thanh-tung, Anh Bui, Le-minh Nguyen, Naoya Inoue
conference: "Arxiv"
year: 2025
bibkey: huutien2025improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.19202"}
tags: ['Security', 'Reinforcement Learning']
---
In this paper, we show that current state-of-the-art LLM unlearning methods inherently reduce models' robustness, causing them to misbehave even when a single non-adversarial forget-token is in the retain-query. Toward understanding underlying causes, we reframe the unlearning process as backdoor attacks and defenses: forget-tokens act as backdoor triggers that, when activated in retain-queries, cause disruptions in unlearned models' behaviors, similar to successful backdoor attacks. To mitigate this vulnerability, we propose Random Noise Augmentation (RNA) -- a plug-and-play, model and method agnostic approach with theoretical guarantees for improving the robustness of unlearned models. Extensive experiments demonstrate that RNA significantly improves the robustness of unlearned models, maintains unlearning performances while introducing no additional computational overhead.
