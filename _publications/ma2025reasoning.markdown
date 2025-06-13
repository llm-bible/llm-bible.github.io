---
layout: publication
title: 'Reasoning Models Can Be Effective Without Thinking'
authors: Wenjie Ma, Jingxuan He, Charlie Snell, Tyler Griggs, Sewon Min, Matei Zaharia
conference: "Arxiv"
year: 2025
bibkey: ma2025reasoning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.09858"}
tags: ['RAG', 'Prompting']
---
Recent LLMs have significantly improved reasoning capabilities, primarily by
including an explicit, lengthy Thinking process as part of generation. In this
paper, we question whether this explicit thinking is necessary. Using the
state-of-the-art DeepSeek-R1-Distill-Qwen, we find that bypassing the thinking
process via simple prompting, denoted as NoThinking, can be surprisingly
effective. When controlling for the number of tokens, NoThinking outperforms
Thinking across a diverse set of seven challenging reasoning
datasets--including mathematical problem solving, formal theorem proving, and
coding--especially in low-budget settings, e.g., 51.3 vs. 28.9 on ACM 23 with
700 tokens. Notably, the performance of NoThinking becomes more competitive
with pass@k as k increases. Building on this observation, we demonstrate that a
parallel scaling approach that uses NoThinking to generate N outputs
independently and aggregates them is highly effective. For aggregation, we use
task-specific verifiers when available, or we apply simple best-of-N strategies
such as confidence-based selection. Our method outperforms a range of baselines
with similar latency using Thinking, and is comparable to Thinking with
significantly longer latency (up to 9x). Together, our research encourages a
reconsideration of the necessity of lengthy thinking processes, while also
establishing a competitive reference for achieving strong reasoning performance
in low-budget settings or at low latency using parallel scaling.
