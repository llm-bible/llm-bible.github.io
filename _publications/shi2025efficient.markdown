---
layout: publication
title: 'Efficient Reinforcement Finetuning Via Adaptive Curriculum Learning'
authors: Taiwei Shi, Yiyang Wu, Linxin Song, Tianyi Zhou, Jieyu Zhao
conference: "Arxiv"
year: 2025
bibkey: shi2025efficient
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.05520'}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Tools', 'Reinforcement Learning']
---
Reinforcement finetuning (RFT) has shown great potential for enhancing the
mathematical reasoning capabilities of large language models (LLMs), but it is
often sample- and compute-inefficient, requiring extensive training. In this
work, we introduce AdaRFT (Adaptive Curriculum Reinforcement Finetuning), a
method that significantly improves both the efficiency and final accuracy of
RFT through adaptive curriculum learning. AdaRFT dynamically adjusts the
difficulty of training problems based on the model's recent reward signals,
ensuring that the model consistently trains on tasks that are challenging but
solvable. This adaptive sampling strategy accelerates learning by maintaining
an optimal difficulty range, avoiding wasted computation on problems that are
too easy or too hard. AdaRFT requires only a lightweight extension to standard
RFT algorithms like Proximal Policy Optimization (PPO), without modifying the
reward function or model architecture. Experiments on competition-level math
datasets-including AMC, AIME, and IMO-style problems-demonstrate that AdaRFT
significantly improves both training efficiency and reasoning performance. We
evaluate AdaRFT across multiple data distributions and model sizes, showing
that it reduces training time by up to 2x and improves accuracy by a
considerable margin, offering a more scalable and effective RFT framework.
