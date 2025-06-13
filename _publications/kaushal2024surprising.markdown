---
layout: publication
title: 'Spectra: Surprising Effectiveness Of Pretraining Ternary Language Models At Scale'
authors: Ayush Kaushal, Tejas Vaidhya, Arnab Kumar Mondal, Tejas Pandey, Aaryan Bhagat, Irina Rish
conference: "Arxiv"
year: 2024
bibkey: kaushal2024surprising
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.12327'}
  - {name: "Code", url: 'https://github.com/NolanoOrg/SpectraSuite'}
tags: ['Has Code', 'Efficiency and Optimization', 'Tools', 'Training Techniques', 'Quantization', 'Pretraining Methods']
---
Rapid advancements in GPU computational power has outpaced memory capacity
and bandwidth growth, creating bottlenecks in Large Language Model (LLM)
inference. Post-training quantization is the leading method for addressing
memory-related bottlenecks in LLM inference, but it suffers from significant
performance degradation below 4-bit precision. This paper addresses these
challenges by investigating the pretraining of low-bitwidth models specifically
Ternary Language Models (TriLMs) as an alternative to traditional
floating-point models (FloatLMs) and their post-training quantized versions
(QuantLMs). We present Spectra LLM suite, the first open suite of LLMs spanning
multiple bit-widths, including FloatLMs, QuantLMs, and TriLMs, ranging from 99M
to 3.9B parameters trained on 300B tokens. Our comprehensive evaluation
demonstrates that TriLMs offer superior scaling behavior in terms of model size
(in bits). Surprisingly, at scales exceeding one billion parameters, TriLMs
consistently outperform their QuantLM and FloatLM counterparts for a given bit
size across various benchmarks. Notably, the 3.9B parameter TriLM matches the
performance of the FloatLM 3.9B across all benchmarks, despite having fewer
bits than FloatLM 830M. Overall, this research provides valuable insights into
the feasibility and scalability of low-bitwidth language models, paving the way
for the development of more efficient LLMs.
  To enhance understanding of low-bitwidth models, we are releasing 500+
intermediate checkpoints of the Spectra suite at
https://github.com/NolanoOrg/SpectraSuite.
