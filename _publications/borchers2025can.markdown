---
layout: publication
title: 'Can Large Language Models Match Tutoring System Adaptivity? A Benchmarking Study'
authors: Conrad Borchers, Tianze Shou
conference: "Arxiv"
year: 2025
bibkey: borchers2025can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.05570"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'GPT', 'Prompting']
---
Large Language Models (LLMs) hold promise as dynamic instructional aids. Yet,
it remains unclear whether LLMs can replicate the adaptivity of intelligent
tutoring systems (ITS)--where student knowledge and pedagogical strategies are
explicitly modeled. We propose a prompt variation framework to assess
LLM-generated instructional moves' adaptivity and pedagogical soundness across
75 real-world tutoring scenarios from an ITS. We systematically remove key
context components (e.g., student errors and knowledge components) from prompts
to create variations of each scenario. Three representative LLMs (Llama3-8B,
Llama3-70B, and GPT-4o) generate 1,350 instructional moves. We use text
embeddings and randomization tests to measure how the omission of each context
feature impacts the LLMs' outputs (adaptivity) and a validated tutor-training
classifier to evaluate response quality (pedagogical soundness). Surprisingly,
even the best-performing model only marginally mimics the adaptivity of ITS.
Specifically, Llama3-70B demonstrates statistically significant adaptivity to
student errors. Although Llama3-8B's recommendations receive higher pedagogical
soundness scores than the other models, it struggles with instruction-following
behaviors, including output formatting. By contrast, GPT-4o reliably adheres to
instructions but tends to provide overly direct feedback that diverges from
effective tutoring, prompting learners with open-ended questions to gauge
knowledge. Given these results, we discuss how current LLM-based tutoring is
unlikely to produce learning benefits rivaling known-to-be-effective ITS
tutoring. Through our open-source benchmarking code, we contribute a
reproducible method for evaluating LLMs' instructional adaptivity and fidelity.
