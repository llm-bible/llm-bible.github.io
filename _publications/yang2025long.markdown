---
layout: publication
title: 'PENCIL: Long Thoughts With Short Memory'
authors: Chenxiao Yang, Nathan Srebro, David Mcallester, Zhiyuan Li
conference: "Arxiv"
year: 2025
bibkey: yang2025long
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.14337"}
tags: ['Training Techniques', 'Model Architecture', 'GPT', 'Pretraining Methods', 'Transformer']
---
While recent works (e.g. o1, DeepSeek R1) have demonstrated great promise of
using long Chain-of-Thought (CoT) to improve reasoning capabilities of language
models, scaling it up during test-time is challenging due to inefficient memory
usage -- intermediate computations accumulate indefinitely in context even no
longer needed for future thoughts. We propose PENCIL, which incorporates a
reduction mechanism into the autoregressive generation process, allowing the
model to recursively clean up intermediate thoughts based on patterns learned
from training. With this reduction mechanism, PENCIL significantly reduces the
maximal context length required during generation, and thus can generate longer
thoughts with limited memory, solving larger-scale problems given more thinking
time. For example, we demonstrate PENCIL achieves 97% accuracy on the
challenging Einstein's puzzle -- a task even large models like GPT-4 struggle
with -- using only a small 25M-parameter transformer with 2048 context length.
Theoretically, we prove PENCIL can perform universal space-efficient
computation by simulating Turing machines with optimal time and space
complexity, and thus can solve arbitrary computational tasks that would
otherwise be intractable given context window constraints.
