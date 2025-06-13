---
layout: publication
title: 'Self-evolved Preference Optimization For Enhancing Mathematical Reasoning In Small Language Models'
authors: Joykirat Singh, Tanmoy Chakraborty, Akshay Nambi
conference: "Arxiv"
year: 2025
bibkey: singh2025self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.04813"}
tags: ['Security', 'Training Techniques', 'Efficiency and Optimization', 'Model Architecture', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
Large language models (LLMs) have significantly improved their reasoning
capabilities; however, they still struggle with complex multi-step mathematical
problem-solving due to error propagation, lack of self-correction, and limited
adaptability to diverse reasoning styles. Existing methods rely on static
fine-tuning or prompt engineering, which fail to generalize across problem
complexities, while the scarcity of high-quality preference data further
hinders reliable reasoning.
  We introduce SPHERE, a self-evolving data generation pipeline that enhances
reasoning in small language models (SLMs) by iteratively generating,
correcting, and diversifying reasoning chains. SPHERE operates in three stages:
(i) Self-Generation, where the model autonomously constructs problem-solving
steps; (ii) Self-Correction, enabling it to identify and rectify errors; and
(iii) Diversity Induction, improving robustness through multiple valid
reasoning trajectories. This self-evolution mechanism strengthens mathematical
reasoning and enhances model reliability. Evaluations on MATH 500, GSM8K, AIME,
AMC, and Olympiad show that SPHERE-trained models achieve significant gains
over their base versions and match/surpass GPT-4o on certain benchmarks. Our
findings demonstrate that self-evolving models can close the reasoning gap
between SLMs and state-of-the-art LLMs, making mathematical AI more reliable,
scalable, and efficient.
