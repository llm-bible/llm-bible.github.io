---
layout: publication
title: 'Smallplan: Leverage Small Language Models For Sequential Path Planning With Simulation-powered, Llm-guided Distillation'
authors: Quang P. M. Pham, Khoi T. N. Nguyen, Nhi H. Doan, Cuong A. Pham, Kentaro Inui, Dezhen Song
conference: "Arxiv"
year: 2025
bibkey: pham2025leverage
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.00831"}
  - {name: "Code", url: "https://github.com/quangpham2006/SmallPlan"}
tags: ['Agentic', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Distillation', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Has Code']
---
Efficient path planning in robotics, particularly within large-scale, dynamic environments, remains a significant hurdle. While Large Language Models (LLMs) offer strong reasoning capabilities, their high computational cost and limited adaptability in dynamic scenarios hinder real-time deployment on edge devices. We present SmallPlan -- a novel framework leveraging LLMs as teacher models to train lightweight Small Language Models (SLMs) for high-level path planning tasks. In SmallPlan, the SLMs provide optimal action sequences to navigate across scene graphs that compactly represent full-scaled 3D scenes. The SLMs are trained in a simulation-powered, interleaved manner with LLM-guided supervised fine-tuning (SFT) and reinforcement learning (RL). This strategy not only enables SLMs to successfully complete navigation tasks but also makes them aware of important factors like travel distance and number of trials. Through experiments, we demonstrate that the fine-tuned SLMs perform competitively with larger models like GPT-4o on sequential path planning, without suffering from hallucination and overfitting. SmallPlan is resource-efficient, making it well-suited for edge-device deployment and advancing practical autonomous robotics. Our source code is available here: https://github.com/quangpham2006/SmallPlan
