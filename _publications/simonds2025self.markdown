---
layout: publication
title: 'Self Rewarding Self Improving'
authors: Toby Simonds, Kevin Lopez, Akira Yoshiyama, Dominique Garmier
conference: "Arxiv"
year: 2025
bibkey: simonds2025self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.08827"}
tags: ['Agentic', 'GPT', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques']
---
We demonstrate that large language models can effectively self-improve through self-judging without requiring reference solutions, leveraging the inherent asymmetry between generating and verifying solutions. Our experiments on Countdown puzzles and MIT Integration Bee problems show that models can provide reliable reward signals without ground truth answers, enabling reinforcement learning in domains previously not possible. By implementing self-judging, we achieve significant performance gains maintaining alignment with formal verification. When combined with synthetic question generation, we establish a complete self-improvement loop where models generate practice problems, solve them, and evaluate their own performance-achieving an 8% improvement with Qwen 2.5 7B over baseline and surpassing GPT-4o performance on integration tasks. Our findings demonstrate that LLM judges can provide effective reward signals for training models, unlocking many reinforcement learning environments previously limited by the difficulty of creating programmatic rewards. This suggests a potential paradigm shift toward AI systems that continuously improve through self-directed learning rather than human-guided training, potentially accelerating progress in domains with scarce training data or complex evaluation requirements.
