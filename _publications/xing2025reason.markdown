---
layout: publication
title: 'Reason-svg: Hybrid Reward RL For Aha-moments In Vector Graphics Generation'
authors: Ximing Xing, Yandong Guan, Jing Zhang, Dong Xu, Qian Yu
conference: "Arxiv"
year: 2025
bibkey: xing2025reason
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.24499"}
tags: ['Fine-Tuning', 'Agentic', 'Efficiency and Optimization', 'Tools', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Generating high-quality Scalable Vector Graphics (SVGs) is challenging for Large Language Models (LLMs), as it requires advanced reasoning for structural validity, semantic faithfulness, and visual coherence -- capabilities in which current LLMs often fall short. In this work, we introduce Reason-SVG, a novel framework designed to enhance LLM reasoning for SVG generation. Reason-SVG pioneers the "Drawing-with-Thought" (DwT) paradigm, in which models generate both SVG code and explicit design rationales, mimicking the human creative process. Reason-SVG adopts a two-stage training strategy: First, Supervised Fine-Tuning (SFT) trains the LLM on the DwT paradigm to activate foundational reasoning abilities. Second, Reinforcement Learning (RL), utilizing Group Relative Policy Optimization (GRPO), empowers the model to generate both DwT and SVGs rationales through refined, reward-driven reasoning. To facilitate reasoning-driven SVG generation, we design a Hybrid Reward function that evaluates the presence and utility of DwT reasoning, along with structural validity, semantic alignment, and visual quality. We also introduce the SVGX-DwT-10k dataset, a high-quality corpus of 10,000 SVG-DwT pairs, where each SVG code is generated based on explicit DwT reasoning. By integrating DwT, SFT, and Hybrid Reward-guided RL, Reason-SVG significantly improves LLM performance in generating accurate and visually compelling SVGs, potentially fostering "Aha moments" in design.
