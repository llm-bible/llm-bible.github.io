---
layout: publication
title: 'Hierarchical Question-answering For Driving Scene Understanding Using Vision-language Models'
authors: Safaa Abdullahi Moallim Mohamud, Minjin Baek, Dong Seog Han
conference: "Arxiv"
year: 2025
bibkey: mohamud2025hierarchical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.02615"}
tags: ['Efficiency and Optimization', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Multimodal Models']
---
In this paper, we present a hierarchical question-answering (QA) approach for scene understanding in autonomous vehicles, balancing cost-efficiency with detailed visual interpretation. The method fine-tunes a compact vision-language model (VLM) on a custom dataset specific to the geographical area in which the vehicle operates to capture key driving-related visual elements. At the inference stage, the hierarchical QA strategy decomposes the scene understanding task into high-level and detailed sub-questions. Instead of generating lengthy descriptions, the VLM navigates a structured question tree, where answering high-level questions (e.g., "Is it possible for the ego vehicle to turn left at the intersection?") triggers more detailed sub-questions (e.g., "Is there a vehicle approaching the intersection from the opposite direction?"). To optimize inference time, questions are dynamically skipped based on previous answers, minimizing computational overhead. The extracted answers are then synthesized using handcrafted templates to ensure coherent, contextually accurate scene descriptions. We evaluate the proposed approach on the custom dataset using GPT reference-free scoring, demonstrating its competitiveness with state-of-the-art methods like GPT-4o in capturing key scene details while achieving significantly lower inference time. Moreover, qualitative results from real-time deployment highlight the proposed approach's capacity to capture key driving elements with minimal latency.
