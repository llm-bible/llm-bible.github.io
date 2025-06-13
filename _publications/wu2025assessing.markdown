---
layout: publication
title: 'Assessing And Mitigating Medical Knowledge Drift And Conflicts In Large Language Models'
authors: Weiyi Wu, Xinwen Xu, Chongyang Gao, Xingjian Diao, Siting Li, Lucas A. Salas, Jiang Gui
conference: "Arxiv"
year: 2025
bibkey: wu2025assessing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.07968"}
tags: ['Security', 'Training Techniques', 'Efficiency and Optimization', 'Tools', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
Large Language Models (LLMs) have great potential in the field of health care, yet they face great challenges in adapting to rapidly evolving medical knowledge. This can lead to outdated or contradictory treatment suggestions. This study investigated how LLMs respond to evolving clinical guidelines, focusing on concept drift and internal inconsistencies. We developed the DriftMedQA benchmark to simulate guideline evolution and assessed the temporal reliability of various LLMs. Our evaluation of seven state-of-the-art models across 4,290 scenarios demonstrated difficulties in rejecting outdated recommendations and frequently endorsing conflicting guidance. Additionally, we explored two mitigation strategies: Retrieval-Augmented Generation and preference fine-tuning via Direct Preference Optimization. While each method improved model performance, their combination led to the most consistent and reliable results. These findings underscore the need to improve LLM robustness to temporal shifts to ensure more dependable applications in clinical practice.
