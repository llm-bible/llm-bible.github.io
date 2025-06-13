---
layout: publication
title: 'Chipalign: Instruction Alignment In Large Language Models For Chip Design Via Geodesic Interpolation'
authors: Chenhui Deng, Yunsheng Bai, Haoxing Ren
conference: "Arxiv"
year: 2024
bibkey: deng2024instruction
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.19819'}
tags: ['Reinforcement Learning', 'Training Techniques', 'Merging']
---
Recent advancements in large language models (LLMs) have expanded their
application across various domains, including chip design, where domain-adapted
chip models like ChipNeMo have emerged. However, these models often struggle
with instruction alignment, a crucial capability for LLMs that involves
following explicit human directives. This limitation impedes the practical
application of chip LLMs, including serving as assistant chatbots for hardware
design engineers. In this work, we introduce ChipAlign, a novel approach that
utilizes a training-free model merging strategy, combining the strengths of a
general instruction-aligned LLM with a chip-specific LLM. By considering the
underlying manifold in the weight space, ChipAlign employs geodesic
interpolation to effectively fuse the weights of input LLMs, producing a merged
model that inherits strong instruction alignment and chip expertise from the
respective instruction and chip LLMs. Our results demonstrate that ChipAlign
significantly enhances instruction-following capabilities of existing chip
LLMs, achieving up to a 26.6% improvement on the IFEval benchmark, while
maintaining comparable expertise in the chip domain. This improvement in
instruction alignment also translates to notable gains in instruction-involved
QA tasks, delivering performance enhancements of 3.9% on the OpenROAD QA
benchmark and 8.25% on production-level chip QA benchmarks, surpassing
state-of-the-art baselines.
