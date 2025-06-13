---
layout: publication
title: 'HPS: Hard Preference Sampling For Human Preference Alignment'
authors: Xiandong Zou, Wanyu Lin, Yuchen Li, Pan Zhou
conference: "Arxiv"
year: 2025
bibkey: zou2025hard
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.14400"}
tags: ['Responsible AI', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG']
---
Aligning Large Language Model (LLM) responses with human preferences is vital for building safe and controllable AI systems. While preference optimization methods based on Plackett-Luce (PL) and Bradley-Terry (BT) models have shown promise, they face challenges such as poor handling of harmful content, inefficient use of dispreferred responses, and, specifically for PL, high computational costs. To address these issues, we propose Hard Preference Sampling (HPS), a novel framework for robust and efficient human preference alignment. HPS introduces a training loss that prioritizes the most preferred response while rejecting all dispreferred and harmful ones. It emphasizes "hard" dispreferred responses -- those closely resembling preferred ones -- to enhance the model's rejection capabilities. By leveraging a single-sample Monte Carlo sampling strategy, HPS reduces computational overhead while maintaining alignment quality. Theoretically, HPS improves sample efficiency over existing PL methods and maximizes the reward margin between preferred and dispreferred responses, ensuring clearer distinctions. Experiments on HH-RLHF and PKU-Safety datasets validate HPS's effectiveness, achieving comparable BLEU and reward scores while greatly improving reward margins and thus reducing harmful content generation.
