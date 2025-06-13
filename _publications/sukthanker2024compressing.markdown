---
layout: publication
title: 'Compressing Large Language Models With Automated Sub-network Search'
authors: Rhea Sanjay Sukthanker, Benedikt Staffler, Frank Hutter, Aaron Klein
conference: "Arxiv"
year: 2024
bibkey: sukthanker2024compressing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.06479"}
tags: ['Efficiency and Optimization', 'RAG', 'Pruning', 'Model Architecture', 'Attention Mechanism', 'Quantization']
---
Large Language Models (LLMs) demonstrate exceptional reasoning abilities,
enabling strong generalization across diverse tasks such as commonsense
reasoning and instruction following. However, as LLMs scale, inference costs
become increasingly prohibitive, accumulating significantly over their life
cycle. In this paper we consider model compression for LLMs to reduce model
size while improving downstream task performance. We phrase this as a neural
architecture search problem that automatically prunes structural components,
such as attention heads, neurons, and layers by searching for the
Pareto-optimal set of sub-networks balancing between performance and on-device
latency. Compared to state-of-the-art structural pruning approaches and
fine-tuned smaller sub-networks extracted from the pre-trained model, our
method achieves upto 9.85% improvement on average on 11 diverse downstream
tasks, while achieving up to 22% improvement of on-device latency.
