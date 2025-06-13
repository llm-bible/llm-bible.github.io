---
layout: publication
title: 'Your Pre-trained LLM Is Secretly An Unsupervised Confidence Calibrator'
authors: Beier Luo, Shuoyuan Wang, Yixuan Li, Hongxin Wei
conference: "Arxiv"
year: 2025
bibkey: luo2025your
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.16690"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'TACL', 'RAG', 'GPT', 'ACL', 'Applications']
---
Post-training of large language models is essential for adapting pre-trained language models (PLMs) to align with human preferences and downstream tasks. While PLMs typically exhibit well-calibrated confidence, post-trained language models (PoLMs) often suffer from over-confidence, assigning high confidence to both correct and incorrect outputs, which can undermine reliability in critical applications. A major obstacle in calibrating PoLMs is the scarcity of labeled data for individual downstream tasks. To address this, we propose Disagreement-Aware Confidence Alignment (DACA), a novel unsupervised method to optimize the parameters (e.g., temperature \\(\tau\\)) in post-hoc confidence calibration. Our method is motivated by the under-confidence issue caused by prediction disagreement between the PLM and PoLM while aligning their confidence via temperature scaling. Theoretically, the PLM's confidence underestimates PoLM's prediction accuracy on disagreement examples, causing a larger \\(\tau\\) and producing under-confident predictions. DACA mitigates this by selectively using only agreement examples for calibration, effectively decoupling the influence of disagreement. In this manner, our method avoids an overly large \\(\tau\\) in temperature scaling caused by disagreement examples, improving calibration performance. Extensive experiments demonstrate the effectiveness of our method, improving the average ECE of open-sourced and API-based LLMs (e.g. GPT-4o) by up to 15.08\\(%\\) on common benchmarks.
