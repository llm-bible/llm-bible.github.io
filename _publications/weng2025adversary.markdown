---
layout: publication
title: 'Adversary-aware DPO: Enhancing Safety Alignment In Vision Language Models Via Adversarial Training'
authors: Fenghua Weng, Jian Lou, Jun Feng, Minlie Huang, Wenjie Wang
conference: "Arxiv"
year: 2025
bibkey: weng2025adversary
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.11455'}
tags: ['Security', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Reinforcement Learning', 'Pre-Training', 'Responsible AI', 'Pretraining Methods']
---
Safety alignment is critical in pre-training large language models (LLMs) to
generate responses aligned with human values and refuse harmful queries. Unlike
LLM, the current safety alignment of VLMs is often achieved with post-hoc
safety fine-tuning. However, these methods are less effective to white-box
attacks. To address this, we propose \\(\textit\{Adversary-aware DPO (ADPO)\}\\), a
novel training framework that explicitly considers adversarial.
\\(\textit\{Adversary-aware DPO (ADPO)\}\\) integrates adversarial training into DPO
to enhance the safety alignment of VLMs under worst-case adversarial
perturbations. \\(\textit\{ADPO\}\\) introduces two key components: (1) an
adversarial-trained reference model that generates human-preferred responses
under worst-case perturbations, and (2) an adversarial-aware DPO loss that
generates winner-loser pairs accounting for adversarial distortions. By
combining these innovations, \\(\textit\{ADPO\}\\) ensures that VLMs remain robust
and reliable even in the presence of sophisticated jailbreak attacks. Extensive
experiments demonstrate that \\(\textit\{ADPO\}\\) outperforms baselines in the
safety alignment and general utility of VLMs.
