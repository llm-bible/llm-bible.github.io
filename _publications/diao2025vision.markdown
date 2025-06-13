---
layout: publication
title: 'Driverx: A Vision-language Reasoning Model For Cross-task Autonomous Driving'
authors: Muxi Diao, Lele Yang, Hongbo Yin, Zhexu Wang, Yejie Wang, Daxin Tian, Kongming Liang, Zhanyu Ma
conference: "Arxiv"
year: 2025
bibkey: diao2025vision
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.20665"}
tags: ['Tools', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Multimodal Models']
---
Autonomous driving requires real-time, robust reasoning across perception, prediction, planning, and behavior. However, conventional end-to-end models fail to generalize in complex scenarios due to the lack of structured reasoning. Recent vision-language models (VLMs) have been applied to driving tasks, but they typically rely on isolated modules and static supervision, limiting their ability to support multi-stage decision-making. We present AutoDriveRL, a unified training framework that formulates autonomous driving as a structured reasoning process over four core tasks. Each task is independently modeled as a vision-language question-answering problem and optimized using task-specific reward models, enabling fine-grained reinforcement signals at different reasoning stages. Within this framework, we train DriveRX, a cross-task reasoning VLM designed for real-time decision-making. DriveRX achieves strong performance on a public benchmark, outperforming GPT-4o in behavior reasoning and demonstrating robustness under complex or corrupted driving conditions. Our analysis further highlights the impact of vision encoder design and reward-guided reasoning compression. We will release the AutoDriveRL framework and the DriveRX model to support future research.
