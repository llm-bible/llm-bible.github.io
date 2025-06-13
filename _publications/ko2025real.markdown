---
layout: publication
title: 'Real-time Verification And Refinement Of Language Model Text Generation'
authors: Joonho Ko, Jinheon Baek, Sung Ju Hwang
conference: "Arxiv"
year: 2025
bibkey: ko2025real
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.07824"}
tags: ['Language Modeling', 'Applications', 'Efficiency and Optimization', 'Reinforcement Learning']
---
Large language models (LLMs) have shown remarkable performance across a wide
range of natural language tasks. However, a critical challenge remains in that
they sometimes generate factually incorrect answers. To address this, while
many previous work has focused on identifying errors in their generation and
further refining them, they are slow in deployment since they are designed to
verify the response from LLMs only after their entire generation (from the
first to last tokens) is done. Further, we observe that once LLMs generate
incorrect tokens early on, there is a higher likelihood that subsequent tokens
will also be factually incorrect. To this end, in this work, we propose
Streaming-VR (Streaming Verification and Refinement), a novel approach designed
to enhance the efficiency of verification and refinement of LLM outputs.
Specifically, the proposed Streaming-VR enables on-the-fly verification and
correction of tokens as they are being generated, similar to a streaming
process, ensuring that each subset of tokens is checked and refined in
real-time by another LLM as the LLM constructs its response. Through
comprehensive evaluations on multiple datasets, we demonstrate that our
approach not only enhances the factual accuracy of LLMs, but also offers a more
efficient solution compared to prior refinement methods.
