---
layout: publication
title: 'Rethinking Textual Adversarial Defense For Pre-trained Language Models'
authors: Wang Jiayi, Bao Rongzhou, Zhang Zhuosheng, Zhao Hai
conference: "Arxiv"
year: 2022
bibkey: wang2022rethinking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2208.10251"}
tags: ['Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Security', 'Tools']
---
Although pre-trained language models (PrLMs) have achieved significant success recent studies demonstrate that PrLMs are vulnerable to adversarial attacks. By generating adversarial examples with slight perturbations on different levels (sentence / word / character) adversarial attacks can fool PrLMs to generate incorrect predictions which questions the robustness of PrLMs. However we find that most existing textual adversarial examples are unnatural which can be easily distinguished by both human and machine. Based on a general anomaly detector we propose a novel metric (Degree of Anomaly) as a constraint to enable current adversarial attack approaches to generate more natural and imperceptible adversarial examples. Under this new constraint the success rate of existing attacks drastically decreases which reveals that the robustness of PrLMs is not as fragile as they claimed. In addition we find that four types of randomization can invalidate a large portion of textual adversarial examples. Based on anomaly detector and randomization we design a universal defense framework which is among the first to perform textual adversarial defense without knowing the specific attack. Empirical results show that our universal defense framework achieves comparable or even higher after-attack accuracy with other specific defenses while preserving higher original accuracy at the same time. Our work discloses the essence of textual adversarial attacks and indicates that (1) further works of adversarial attacks should focus more on how to overcome the detection and resist the randomization otherwise their adversarial examples would be easily detected and invalidated; and (2) compared with the unnatural and perceptible adversarial examples it is those undetectable adversarial examples that pose real risks for PrLMs and require more attention for future robustness-enhancing strategies.
