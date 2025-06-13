---
layout: publication
title: 'Smaller But Better: Unifying Layout Generation With Smaller Large Language Models'
authors: Peirong Zhang, Jiaxin Zhang, Jiahuan Cao, Hongliang Li, Lianwen Jin
conference: "Arxiv"
year: 2025
bibkey: zhang2025smaller
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.14005"}
  - {name: "Code", url: "https://github.com/NiceRingNode/LGGPT"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'GPT', 'Quantization', 'Has Code']
---
We propose LGGPT, an LLM-based model tailored for unified layout generation.
First, we propose Arbitrary Layout Instruction (ALI) and Universal Layout
Response (ULR) as the uniform I/O template. ALI accommodates arbitrary layout
generation task inputs across multiple layout domains, enabling LGGPT to unify
both task-generic and domain-generic layout generation hitherto unexplored.
Collectively, ALI and ULR boast a succinct structure that forgoes superfluous
tokens typically found in existing HTML-based formats, facilitating efficient
instruction tuning and boosting unified generation performance. In addition, we
propose an Interval Quantization Encoding (IQE) strategy that compresses ALI
into a more condensed structure. IQE precisely preserves valid layout clues
while eliminating the less informative placeholders, facilitating LGGPT to
capture complex and variable layout generation conditions during the unified
training process. Experimental results demonstrate that LGGPT achieves superior
or on par performance compared to existing methods. Notably, LGGPT strikes a
prominent balance between proficiency and efficiency with a compact 1.5B
parameter LLM, which beats prior 7B or 175B models even in the most extensive
and challenging unified scenario. Furthermore, we underscore the necessity of
employing LLMs for unified layout generation and suggest that 1.5B could be an
optimal parameter size by comparing LLMs of varying scales. Code is available
at https://github.com/NiceRingNode/LGGPT.
