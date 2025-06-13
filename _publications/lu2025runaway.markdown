---
layout: publication
title: 'Runaway Is Ashamed, But Helpful: On The Early-exit Behavior Of Large Language Model-based Agents In Embodied Environments'
authors: Qingyu Lu, Liang Ding, Siyi Cao, Xuebo Liu, Kanjian Zhang, Jinxia Zhang, Dacheng Tao
conference: "Arxiv"
year: 2025
bibkey: lu2025runaway
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.17616'}
tags: ['Reinforcement Learning', 'Agentic', 'Efficiency and Optimization']
---
Agents powered by large language models (LLMs) have demonstrated strong planning and decision-making capabilities in complex embodied environments. However, such agents often suffer from inefficiencies in multi-turn interactions, frequently trapped in repetitive loops or issuing ineffective commands, leading to redundant computational overhead. Instead of relying solely on learning from trajectories, we take a first step toward exploring the early-exit behavior for LLM-based agents. We propose two complementary approaches: 1. an \\(\textbf\{intrinsic\}\\) method that injects exit instructions during generation, and 2. an \\(\textbf\{extrinsic\}\\) method that verifies task completion to determine when to halt an agent's trial. To evaluate early-exit mechanisms, we introduce two metrics: one measures the reduction of \\(\textbf\{redundant steps\}\\) as a positive effect, and the other evaluates \\(\textbf\{progress degradation\}\\) as a negative effect. Experiments with 4 different LLMs across 5 embodied environments show significant efficiency improvements, with only minor drops in agent performance. We also validate a practical strategy where a stronger agent assists after an early-exit agent, achieving better performance with the same total steps. We will release our code to support further research.
