---
layout: publication
title: 'Inference Scaling Vs Reasoning: An Empirical Analysis Of Compute-optimal LLM Problem-solving'
authors: Marwan Abdelhameed, Pavly Halim
conference: "Arxiv"
year: 2024
bibkey: abdelhameed2024inference
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.16260'}
tags: ['Reinforcement Learning', 'Efficiency and Optimization', 'Model Architecture']
---
Recent advances in large language models (LLMs) have predominantly focused on
maximizing accuracy and reasoning capabilities, often overlooking crucial
computational efficiency considerations. While this approach has yielded
impressive accuracy improvements, it has led to methods that may be impractical
for real-world deployment due to computational overhead and latency
constraints. This paper investigates the potential synergy between reasoning
enhancement and computational efficiency by analyzing the integration of two
contrasting approaches: Quiet-STaR (Self-Taught Reasoner) and REBASE (REward
BAlanced SEarch). Through comprehensive empirical analysis using the Mistral-7B
model on the GSM8K dataset, we demonstrate that while each method excels in its
primary objective-Quiet-STaR achieving superior accuracy (32.03%) despite high
computational cost (554.66s runtime, 12.73T FLOPs), and REBASE providing
exceptional efficiency (8.47s runtime, 2.35T FLOPs) while maintaining
baseline-comparable accuracy (10.94%)-their integration reveals fundamental
challenges in reconciling reasoning depth with computational efficiency. The
combined approach unexpectedly results in degraded performance (9.38% accuracy,
143.66s runtime), highlighting critical insights about the complex interplay
between reasoning enhancement and efficiency optimization in LLMs. Our findings
illuminate the need for novel architectures and algorithms specifically
designed to bridge the gap between these competing objectives, while providing
concrete directions for future research in compute-efficient reasoning methods.
