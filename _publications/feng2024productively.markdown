---
layout: publication
title: 'Productively Deploying Emerging Models On Emerging Platforms: A Top-down Approach For Testing And Debugging'
authors: Siyuan Feng, Jiawei Liu, Ruihang Lai, Charlie F. Ruan, Yong Yu, Lingming Zhang, Tianqi Chen
conference: "Arxiv"
year: 2024
bibkey: feng2024productively
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.09151"}
tags: ['Tools', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Merging']
---
While existing machine learning (ML) frameworks focus on established
platforms, like running CUDA on server-grade GPUs, there have been growing
demands to enable emerging AI applications in a broader set of scenarios, such
as running Large Language Models (LLMs) within browsers and mobile phones.
However, deploying emerging models on new platforms (such as Metal and WebGPU)
presents significant software engineering challenges due to rapid model
evolution and limited tooling and practices for these platforms.
  Previous practice for ML model deployment often follows a bottom-up fashion,
where engineers first implement individual required operators and then put them
together. However, this traditional development approach fails to meet the
productivity requirements when deploying emerging ML applications, with the
testing and debugging part as a bottleneck. To this end, we introduce
\textsc\{TapML\}, a top-down approach designed to streamline model deployment on
diverse platforms. While the traditional bottom-up approach requires crafting
manual tests, \textsc\{TapML\} automatically creates high-quality, realistic test
data through operator-wise test carving. Furthermore, \textsc\{TapML\} uses a
migration-based strategy to gradually offload model implementation from the
mature source platform to the target platform, minimizing the debugging scope
of compound errors.
  \textsc\{TapML\} has been used as the default development method in the MLC-LLM
project to deploy emerging ML models. Within 2 years, \textsc\{TapML\} has
accelerated the deployment of 105 emerging models in 27 model architectures
across 5 emerging platforms. We show that \textsc\{TapML\} effectively boosts
developer productivity while ensuring the quality of deployed models.
Furthermore, we summarize comprehensive case studies from our real-world
development, offering best practices for developing emerging ML systems.
