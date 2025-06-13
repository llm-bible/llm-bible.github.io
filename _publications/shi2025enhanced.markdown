---
layout: publication
title: 'Smartway: Enhanced Waypoint Prediction And Backtracking For Zero-shot Vision-and-language Navigation'
authors: Xiangyu Shi, Zerui Li, Wenqi Lyu, Jiatong Xia, Feras Dayoub, Yanyuan Qiao, Qi Wu
conference: "Arxiv"
year: 2025
bibkey: shi2025enhanced
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.10069"}
tags: ['Agentic', 'Security', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Merging', 'Attention Mechanism']
---
Vision-and-Language Navigation (VLN) in continuous environments requires
agents to interpret natural language instructions while navigating
unconstrained 3D spaces. Existing VLN-CE frameworks rely on a two-stage
approach: a waypoint predictor to generate waypoints and a navigator to execute
movements. However, current waypoint predictors struggle with spatial
awareness, while navigators lack historical reasoning and backtracking
capabilities, limiting adaptability. We propose a zero-shot VLN-CE framework
integrating an enhanced waypoint predictor with a Multi-modal Large Language
Model (MLLM)-based navigator. Our predictor employs a stronger vision encoder,
masked cross-attention fusion, and an occupancy-aware loss for better waypoint
quality. The navigator incorporates history-aware reasoning and adaptive path
planning with backtracking, improving robustness. Experiments on R2R-CE and
MP3D benchmarks show our method achieves state-of-the-art (SOTA) performance in
zero-shot settings, demonstrating competitive results compared to fully
supervised methods. Real-world validation on Turtlebot 4 further highlights its
adaptability.
