---
layout: publication
title: "Enhancing Q-learning With Large Language Model Heuristics"
authors: Wu Xiefeng
conference: "Arxiv"
year: 2024
bibkey: wu2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.03341"}
tags: ['Agentic', 'Efficiency And Optimization', 'Ethics And Bias', 'Fine Tuning', 'RAG', 'Reinforcement Learning', 'Tools']
---
Q-learning excels in learning from feedback within sequential decision-making tasks but often requires extensive sampling to achieve significant improvements. While reward shaping can enhance learning efficiency non-potential-based methods introduce biases that affect performance and potential-based reward shaping though unbiased lacks the ability to provide heuristics for state-action pairs limiting its effectiveness in complex environments. Large language models (LLMs) can achieve zero-shot learning for simpler tasks but they suffer from low inference speeds and occasional hallucinations. To address these challenges we propose (textbf)LLM-guided Q-learning a framework that leverages LLMs as heuristics to aid in learning the Q-function for reinforcement learning. Our theoretical analysis demonstrates that this approach adapts to hallucinations improves sample efficiency and avoids biasing final performance. Experimental results show that our algorithm is general robust and capable of preventing ineffective exploration.
