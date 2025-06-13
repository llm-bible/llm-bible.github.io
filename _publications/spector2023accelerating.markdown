---
layout: publication
title: 'Accelerating LLM Inference With Staged Speculative Decoding'
authors: Benjamin Spector, Chris Re
conference: "Arxiv"
year: 2023
bibkey: spector2023accelerating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.04623"}
tags: ['Model Architecture', 'GPT']
---
Recent advances with large language models (LLM) illustrate their diverse
capabilities. We propose a novel algorithm, staged speculative decoding, to
accelerate LLM inference in small-batch, on-device scenarios. We address the
low arithmetic intensity of small-batch inference by improving upon previous
work in speculative decoding. First, we restructure the speculative batch as a
tree, which reduces generation costs and increases the expected tokens per
batch. Second, we add a second stage of speculative decoding. Taken together,
we reduce single-batch decoding latency by 3.16x with a 762M parameter GPT-2-L
model while perfectly preserving output quality.
