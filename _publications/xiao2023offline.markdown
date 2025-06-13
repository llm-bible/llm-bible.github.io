---
layout: publication
title: 'O3D: Offline Data-driven Discovery And Distillation For Sequential Decision-making With Large Language Models'
authors: Yuchen Xiao, Yanchao Sun, Mengda Xu, Udari Madhushani, Jared Vann, Deepeka Garg, Sumitra Ganesh
conference: "Arxiv"
year: 2023
bibkey: xiao2023offline
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.14403"}
tags: ['Agentic', 'Efficiency and Optimization', 'Tools', 'Reinforcement Learning', 'Training Techniques', 'In-Context Learning', 'Few-Shot', 'Prompting', 'Distillation']
---
Recent advancements in large language models (LLMs) have exhibited promising
performance in solving sequential decision-making problems. By imitating
few-shot examples provided in the prompts (i.e., in-context learning), an LLM
agent can interact with an external environment and complete given tasks
without additional training. However, such few-shot examples are often
insufficient to generate high-quality solutions for complex and long-horizon
tasks, while the limited context length cannot consume larger-scale
demonstrations with long interaction horizons. To this end, we propose an
offline learning framework that utilizes offline data at scale (e.g, logs of
human interactions) to improve LLM-powered policies without finetuning. The
proposed method O3D (Offline Data-driven Discovery and Distillation)
automatically discovers reusable skills and distills generalizable knowledge
across multiple tasks based on offline interaction data, advancing the
capability of solving downstream tasks. Empirical results under two interactive
decision-making benchmarks (ALFWorld and WebShop) verify that O3D can notably
enhance the decision-making capabilities of LLMs through the offline discovery
and distillation process, and consistently outperform baselines across various
LLMs.
