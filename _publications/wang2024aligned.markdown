---
layout: publication
title: 'ASFT: Aligned Supervised Fine-tuning Through Absolute Likelihood'
authors: Ruoyu Wang, Jiachen Sun, Shaowei Hua, Quan Fang
conference: "Arxiv"
year: 2024
bibkey: wang2024aligned
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.10571"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Reinforcement Learning', 'Language Modeling', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
Direct Preference Optimization (DPO) is a method for enhancing model
performance by directly optimizing for the preferences or rankings of outcomes,
instead of traditional loss functions. This approach has proven effective in
aligning Large Language Models (LLMs) with human preferences. Despite its
widespread use across various tasks, DPO has been criticized for its
sensitivity to the effectiveness of Supervised Fine-Tuning (SFT) and its
limitations in enabling models to learn human-preferred responses, leading to
less satisfactory performance. To address these limitations, we propose Aligned
Supervised Fine-Tuning (ASFT), an effective approach that better aligns LLMs
with pair-wise datasets by optimizing absolute likelihood for each response,
rather than using the Bradley-Terry model, and eliminates the need for a
reference model. Through theoretical gradient analysis, we demonstrate that
ASFT mitigates the issue where the DPO loss function decreases the probability
of generating human-dispreferred data at a faster rate than it increases the
probability of producing preferred data. Additionally, we compare ASFT to DPO
and its latest variants, such as the single-step approach ORPO, using the
latest instruction-tuned model Llama3, which has been fine-tuned on
UltraFeedback and HH-RLHF. We evaluated performance on instruction-following
benchmarks like MT-Bench and traditional text generation metrics such as BLEU-4
and ROUGE-L. Extensive experiments demonstrate that ASFT is an effective
alignment approach, consistently outperforming existing methods.
