---
layout: publication
title: 'Large Language Models Struggle With Unreasonability In Math Problems'
authors: Jingyuan Ma, Damai Dai, Zihang Yuan, Rui Li, Weilin Luo, Bin Wang, Qun Liu, Lei Sha, Zhifang Sui
conference: "Arxiv"
year: 2024
bibkey: ma2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.19346"}
tags: ['Security', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
Large Language Models (LLMs) have shown remarkable success on a wide range of math and reasoning benchmarks. However, we observe that they often struggle when faced with unreasonable math problems. Instead of recognizing these issues, models frequently proceed as if the problem is well-posed, producing incorrect answers or falling into overthinking and verbose self-correction. To systematically investigate this overlooked vulnerability, we propose the \textbf\{Unreasonable Math Problems (UMP)\} benchmark, designed to evaluate LLMs' ability to detect and respond to unreasonable math problem statements. Based on extensive experiments covering 19 LLMs, we find that even state-of-the-art general models like GPT-4o achieve only a score of 0.6 on UMP. While reasoning models such as DeepSeek-R1 demonstrate a higher sensitivity to unreasonable inputs, this often comes at the cost of generating overly long and meaningless responses that fail to converge. We further explore prompting and fine-tuning methods, which offer partial improvements but also introduce trade-offs, shedding light on both the potential and limitations of LLMs in this challenging setting.
