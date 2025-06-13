---
layout: publication
title: 'On The Reasoning Capacity Of AI Models And How To Quantify It'
authors: Santosh Kumar Radha, Oktay Goktas
conference: "Arxiv"
year: 2025
bibkey: radha2025reasoning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.13833"}
tags: ['Ethics and Bias', 'Applications', 'Tools', 'Reinforcement Learning']
---
Recent advances in Large Language Models (LLMs) have intensified the debate
surrounding the fundamental nature of their reasoning capabilities. While
achieving high performance on benchmarks such as GPQA and MMLU, these models
exhibit limitations in more complex reasoning tasks, highlighting the need for
more rigorous evaluation methodologies. We propose a novel phenomenological
approach that goes beyond traditional accuracy metrics to probe the underlying
mechanisms of model behavior, establishing a framework that could broadly
impact how we analyze and understand AI systems. Using positional bias in
multiple-choice reasoning tasks as a case study, we demonstrate how systematic
perturbations can reveal fundamental aspects of model decision-making. To
analyze these behaviors, we develop two complementary phenomenological models:
a Probabilistic Mixture Model (PMM) that decomposes model responses into
reasoning, memorization, and guessing components and an Information-Theoretic
Consistency (ITC) analysis that quantifies the relationship between model
confidence and strategy selection. Through controlled experiments on reasoning
benchmarks, we show that true reasoning remains challenging for current models,
with apparent success often relying on sophisticated combinations of
memorization and pattern matching rather than genuine logical deduction. More
fundamentally, we demonstrate that accuracy alone often overstates a model's
reasoning abilities, as model behavior can be characterized through underlying
mechanisms in the phase space of cognitive strategies, revealing how models
dynamically balance different approaches when responding to queries. This
framework enables quantitative criteria for real-world deployments, allowing
applications to specify reliability thresholds based on strategy distributions
rather than aggregate performance metrics.
