---
layout: publication
title: 'Vending-bench: A Benchmark For Long-term Coherence Of Autonomous Agents'
authors: Axel Backlund, Lukas Petersson
conference: "Arxiv"
year: 2025
bibkey: backlund2025vending
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.15840"}
tags: ['Agentic', 'Agent', 'Tools']
---
While Large Language Models (LLMs) can exhibit impressive proficiency in
isolated, short-term tasks, they often fail to maintain coherent performance
over longer time horizons. In this paper, we present Vending-Bench, a simulated
environment designed to specifically test an LLM-based agent's ability to
manage a straightforward, long-running business scenario: operating a vending
machine. Agents must balance inventories, place orders, set prices, and handle
daily fees - tasks that are each simple but collectively, over long horizons
(>20M tokens per run) stress an LLM's capacity for sustained, coherent
decision-making. Our experiments reveal high variance in performance across
multiple LLMs: Claude 3.5 Sonnet and o3-mini manage the machine well in most
runs and turn a profit, but all models have runs that derail, either through
misinterpreting delivery schedules, forgetting orders, or descending into
tangential "meltdown" loops from which they rarely recover. We find no clear
correlation between failures and the point at which the model's context window
becomes full, suggesting that these breakdowns do not stem from memory limits.
Apart from highlighting the high variance in performance over long time
horizons, Vending-Bench also tests models' ability to acquire capital, a
necessity in many hypothetical dangerous AI scenarios. We hope the benchmark
can help in preparing for the advent of stronger AI systems.
