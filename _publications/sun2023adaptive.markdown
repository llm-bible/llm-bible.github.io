---
layout: publication
title: Adaplanner&#58; Adaptive Planning From Feedback With Language Models
authors: Sun Haotian, Zhuang Yuchen, Kong Lingkai, Dai Bo, Zhang Chao
conference: "Arxiv"
year: 2023
bibkey: sun2023adaptive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.16653"}
tags: ['Agent', 'Agentic', 'Few Shot', 'Prompting', 'RAG', 'Reinforcement Learning']
---
Large language models (LLMs) have recently demonstrated the potential in acting as autonomous agents for sequential decision-making tasks. However most existing methods either take actions greedily without planning or rely on static plans that are not adaptable to environmental feedback. Consequently the sequential decision-making performance of LLM agents degenerates with problem complexity and plan horizons increase. We propose a closed-loop approach AdaPlanner which allows the LLM agent to refine its self-generated plan adaptively in response to environmental feedback. In AdaPlanner the LLM agent adaptively refines its plan from feedback with both in-plan and out-of-plan refinement strategies. To mitigate hallucination we develop a code-style LLM prompt structure that facilitates plan generation across a variety of tasks environments and agent capabilities. Furthermore we propose a skill discovery mechanism that leverages successful plans as few-shot exemplars enabling the agent to plan and refine with fewer task demonstrations. Our experiments in the ALFWorld and MiniWoB++ environments demonstrate that AdaPlanner outperforms state-of-the-art baselines by 3.7337; and 4.1137; while utilizing 2x and 600x fewer samples respectively.
