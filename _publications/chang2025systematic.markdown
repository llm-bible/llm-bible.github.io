---
layout: publication
title: 'A Systematic Approach For Assessing Large Language Models'' Test Case Generation Capability'
authors: Hung-fu Chang, Mohammad Shokrolah Shirazi
conference: "Arxiv"
year: 2025
bibkey: chang2025systematic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.02866"}
tags: ['Tools', 'GPT', 'RAG', 'Model Architecture', 'Reinforcement Learning']
---
Software testing ensures the quality and reliability of software products,
but manual test case creation is labor-intensive. With the rise of large
language models (LLMs), there is growing interest in unit test creation with
LLMs. However, effective assessment of LLM-generated test cases is limited by
the lack of standardized benchmarks that comprehensively cover diverse
programming scenarios. To address the assessment of LLM's test case generation
ability and lacking dataset for evaluation, we propose the Generated Benchmark
from Control-Flow Structure and Variable Usage Composition (GBCV) approach,
which systematically generates programs used for evaluating LLMs' test
generation capabilities. By leveraging basic control-flow structures and
variable usage, GBCV provides a flexible framework to create a spectrum of
programs ranging from simple to complex. Because GPT-4o and GPT-3-Turbo are
publicly accessible models, to present real-world regular user's use case, we
use GBCV to assess LLM performance on them. Our findings indicate that GPT-4o
performs better on complex program structures, while all models effectively
detect boundary values in simple conditions but face challenges with arithmetic
computations. This study highlights the strengths and limitations of LLMs in
test generation, provides a benchmark framework, and suggests directions for
future improvement.
