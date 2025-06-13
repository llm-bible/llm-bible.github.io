---
layout: publication
title: 'Restoring Calibration For Aligned Large Language Models: A Calibration-aware Fine-tuning Approach'
authors: Jiancong Xiao, Bojian Hou, Zhanliang Wang, Ruochen Jin, Qi Long, Weijie J. Su, Li Shen
conference: "ICML 2025"
year: 2025
bibkey: xiao2025restoring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.01997"}
tags: ['Pretraining Methods', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning']
---
One of the key technologies for the success of Large Language Models (LLMs)
is preference alignment. However, a notable side effect of preference alignment
is poor calibration: while the pre-trained models are typically
well-calibrated, LLMs tend to become poorly calibrated after alignment with
human preferences. In this paper, we investigate why preference alignment
affects calibration and how to address this issue. For the first question, we
observe that the preference collapse issue in alignment undesirably generalizes
to the calibration scenario, causing LLMs to exhibit overconfidence and poor
calibration. To address this, we demonstrate the importance of fine-tuning with
domain-specific knowledge to alleviate the overconfidence issue. To further
analyze whether this affects the model's performance, we categorize models into
two regimes: calibratable and non-calibratable, defined by bounds of Expected
Calibration Error (ECE). In the calibratable regime, we propose a
calibration-aware fine-tuning approach to achieve proper calibration without
compromising LLMs' performance. However, as models are further fine-tuned for
better performance, they enter the non-calibratable regime. For this case, we
develop an EM-algorithm-based ECE regularization for the fine-tuning loss to
maintain low calibration error. Extensive experiments validate the
effectiveness of the proposed methods.
