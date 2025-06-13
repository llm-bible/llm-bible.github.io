---
layout: publication
title: 'Can Language Models Falsify? Evaluating Algorithmic Reasoning With Counterexample Creation'
authors: Shiven Sinha, Shashwat Goel, Ponnurangam Kumaraguru, Jonas Geiping, Matthias Bethge, Ameya Prabhu
conference: "Arxiv"
year: 2025
bibkey: sinha2025can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.19414"}
tags: ['Agentic']
---
There is growing excitement about the potential of Language Models (LMs) to
accelerate scientific discovery. Falsifying hypotheses is key to scientific
progress, as it allows claims to be iteratively refined over time. This process
requires significant researcher effort, reasoning, and ingenuity. Yet current
benchmarks for LMs predominantly assess their ability to generate solutions
rather than challenge them. We advocate for developing benchmarks that evaluate
this inverse capability - creating counterexamples for subtly incorrect
solutions. To demonstrate this approach, we start with the domain of
algorithmic problem solving, where counterexamples can be evaluated
automatically using code execution. Specifically, we introduce REFUTE, a
dynamically updating benchmark that includes recent problems and incorrect
submissions from programming competitions, where human experts successfully
identified counterexamples. Our analysis finds that the best reasoning agents,
even OpenAI o3-mini (high) with code execution feedback, can create
counterexamples for only <9% of incorrect solutions in REFUTE, even though
ratings indicate its ability to solve up to 48% of these problems from scratch.
We hope our work spurs progress in evaluating and enhancing LMs' ability to
falsify incorrect solutions - a capability that is crucial for both
accelerating research and making models self-improve through reliable
reflective reasoning.
