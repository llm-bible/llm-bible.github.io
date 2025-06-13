---
layout: publication
title: 'How Well Do Llms Compress Their Own Chain-of-thought? A Token Complexity Approach'
authors: Ayeong Lee, Ethan Che, Tianyi Peng
conference: "Arxiv"
year: 2025
bibkey: lee2025how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.01141"}
tags: ['Tools', 'Efficiency and Optimization', 'Prompting']
---
Chain-of-thought prompting has emerged as a powerful technique for enabling
large language models (LLMs) to solve complex reasoning tasks. However, these
reasoning chains can be verbose, raising concerns about efficiency. In
response, recent works have sought to decrease response lengths through simple
prompting strategies (e.g. 'be concise'). In this work, we conduct the first
systematic study of the relationship between reasoning length and model
performance across a diverse range of compression instructions (e.g. 'use 10
words or less' or 'remove all punctuation'). In doing so, we discover a
universal tradeoff between reasoning length and accuracy that persists across
even very distinct reasoning chains. We demonstrate that this tradeoff emerges
from a sharp threshold behavior at the question level: each task has an
intrinsic 'token complexity' - a minimal number of tokens required for
successful problem-solving. We show how token complexity enables us to compute
information-theoretic limits on the accuracy-compression tradeoff, and find
that prompt-based compression strategies operate far from these theoretical
limits. This suggests there may be significant room for improvement and our
framework provides a benchmark to help researchers evaluate progress in
reasoning efficiency. Our work also highlights the importance of adaptive
compression -- giving shorter responses for easier questions -- and we show
that token complexity is a useful tool for measuring this capability.
