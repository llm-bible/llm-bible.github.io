---
layout: publication
title: 'UAV-VLN: End-to-end Vision Language Guided Navigation For Uavs'
authors: Pranav Saxena, Nishant Raghuvanshi, Neena Goveas
conference: "Arxiv"
year: 2025
bibkey: saxena2025uav
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.21432'}
tags: ['Agentic', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Multimodal Models']
---
A core challenge in AI-guided autonomy is enabling agents to navigate
realistically and effectively in previously unseen environments based on
natural language commands. We propose UAV-VLN, a novel end-to-end
Vision-Language Navigation (VLN) framework for Unmanned Aerial Vehicles (UAVs)
that seamlessly integrates Large Language Models (LLMs) with visual perception
to facilitate human-interactive navigation. Our system interprets free-form
natural language instructions, grounds them into visual observations, and plans
feasible aerial trajectories in diverse environments.
  UAV-VLN leverages the common-sense reasoning capabilities of LLMs to parse
high-level semantic goals, while a vision model detects and localizes
semantically relevant objects in the environment. By fusing these modalities,
the UAV can reason about spatial relationships, disambiguate references in
human instructions, and plan context-aware behaviors with minimal task-specific
supervision. To ensure robust and interpretable decision-making, the framework
includes a cross-modal grounding mechanism that aligns linguistic intent with
visual context.
  We evaluate UAV-VLN across diverse indoor and outdoor navigation scenarios,
demonstrating its ability to generalize to novel instructions and environments
with minimal task-specific training. Our results show significant improvements
in instruction-following accuracy and trajectory efficiency, highlighting the
potential of LLM-driven vision-language interfaces for safe, intuitive, and
generalizable UAV autonomy.
