---
layout: publication
title: Active Preference Optimization For Sample Efficient RLHF
authors: Das Nirjhar, Chakraborty Souradip, Pacchiano Aldo, Chowdhury Sayak Ray
conference: "Arxiv"
year: 2024
bibkey: das2024active
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.10500"}
tags: ['Agentic', 'Efficiency And Optimization', 'Prompting', 'Reinforcement Learning', 'Tools']
---
Reinforcement Learning from Human Feedback (RLHF) is pivotal in aligning Large Language Models (LLMs) with human preferences. Although aligned generative models have shown remarkable abilities in various tasks their reliance on high45;quality human preference data creates a costly bottleneck in the practical application of RLHF. One primary reason is that current methods rely on uniformly picking prompt45;generation pairs from a dataset of prompt45;generations to collect human feedback resulting in sub45;optimal alignment under a constrained budget which highlights the criticality of adaptive strategies in efficient alignment. Recent works Mehta et al. 2023 Muldrew et al. 2024 have tried to address this problem by designing various heuristics based on generation uncertainty. However either the assumptions in Mehta et al. 2023 are restrictive or Muldrew et al. 2024 do not provide any rigorous theoretical guarantee. To address these we reformulate RLHF within contextual preference bandit framework treating prompts as contexts and develop an active45;learning algorithm textit123;Active Preference Optimization125; (texttt123;APO125;) which enhances model alignment by querying preference data from the most important samples achieving superior performance for small sample budget. We analyze the theoretical performance guarantees of texttt123;APO125; under the BTL preference model showing that the suboptimality gap of the policy learned via texttt123;APO125; scales as O(1/sqrt123;T125;) for a budget of T. We also show that collecting preference data by choosing prompts randomly leads to a policy that suffers a constant sub45;optimality. We perform detailed experimental evaluations on practical preference datasets to validate texttt123;APO125;s efficacy over the existing methods establishing it as a sample45;efficient and practical solution of alignment in a cost45;effective and scalable manner.
