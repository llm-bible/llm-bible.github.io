---
layout: publication
title: Instructioncp\: A Fast Approach To Transfer Large Language Models Into Target Language
authors: Chen Kuang-ming, Lee Hung-yi
conference: "Arxiv"
year: 2024
bibkey: chen2024fast
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.20175"}
tags: ['Agentic', 'Fine Tuning', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
The rapid development of large language models (LLMs) in recent years has largely focused on English resulting in models that respond exclusively in English. To adapt these models to other languages continual pre-training (CP) is often employed followed by supervised fine-tuning (SFT) to maintain conversational abilities. However CP and SFT can reduce a models ability to filter harmful content. We propose Instruction Continual Pre-training (InsCP) which integrates instruction tags into the CP process to prevent loss of conversational proficiency while acquiring new languages. Our experiments demonstrate that InsCP retains conversational and Reinforcement Learning from Human Feedback (RLHF) abilities. Empirical evaluations on language alignment reliability and knowledge benchmarks confirm the efficacy of InsCP. Notably this approach requires only 0.1 billion tokens of high-quality instruction-following data thereby reducing resource consumption.
