---
layout: publication
title: 'Visual-rft: Visual Reinforcement Fine-tuning'
authors: Ziyu Liu, Zeyi Sun, Yuhang Zang, Xiaoyi Dong, Yuhang Cao, Haodong Duan, Dahua Lin, Jiaqi Wang
conference: "Arxiv"
year: 2025
bibkey: liu2025visual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.01785"}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Multimodal Models', 'Few-Shot', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
Reinforcement Fine-Tuning (RFT) in Large Reasoning Models like OpenAI o1
learns from feedback on its answers, which is especially useful in applications
when fine-tuning data is scarce. Recent open-source work like DeepSeek-R1
demonstrates that reinforcement learning with verifiable reward is one key
direction in reproducing o1. While the R1-style model has demonstrated success
in language models, its application in multi-modal domains remains
under-explored. This work introduces Visual Reinforcement Fine-Tuning
(Visual-RFT), which further extends the application areas of RFT on visual
tasks. Specifically, Visual-RFT first uses Large Vision-Language Models (LVLMs)
to generate multiple responses containing reasoning tokens and final answers
for each input, and then uses our proposed visual perception verifiable reward
functions to update the model via the policy optimization algorithm such as
Group Relative Policy Optimization (GRPO). We design different verifiable
reward functions for different perception tasks, such as the Intersection over
Union (IoU) reward for object detection. Experimental results on fine-grained
image classification, few-shot object detection, reasoning grounding, as well
as open-vocabulary object detection benchmarks show the competitive performance
and advanced generalization ability of Visual-RFT compared with Supervised
Fine-tuning (SFT). For example, Visual-RFT improves accuracy by \\(24.3%\\) over
the baseline in one-shot fine-grained image classification with around 100
samples. In few-shot object detection, Visual-RFT also exceeds the baseline by
\\(21.9\\) on COCO's two-shot setting and \\(15.4\\) on LVIS. Our Visual-RFT represents
a paradigm shift in fine-tuning LVLMs, offering a data-efficient, reward-driven
approach that enhances reasoning and adaptability for domain-specific tasks.
