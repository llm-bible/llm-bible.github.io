---
layout: publication
title: The Fault In Our Stars&#58; Quality Assessment Of Code Generation Benchmarks
authors: Siddiq Mohammed Latif, Dristi Simantika, Saha Joy, Santos Joanna C. S.
conference: "Arxiv"
year: 2024
bibkey: siddiq2024fault
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.10155"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Prompting']
---
Large Language Models (LLMs) are gaining popularity among software engineers. A crucial aspect of developing effective code generation LLMs is to evaluate these models using a robust benchmark. Evaluation benchmarks with quality issues can provide a false sense of performance. In this work we conduct the first-of-its-kind study of the quality of prompts within benchmarks used to compare the performance of different code generation models. To conduct this study we analyzed 3566 prompts from 9 code generation benchmarks to identify quality issues in them. We also investigated whether fixing the identified quality issues in the benchmarks prompts affects a models performance. We also studied memorization issues of the evaluation dataset which can put into question a benchmarks trustworthiness. We found that code generation evaluation benchmarks mainly focused on Python and coding exercises and had very limited contextual dependencies to challenge the model. These datasets and the developers prompts suffer from quality issues like spelling and grammatical errors unclear sentences to express developers intent and not using proper documentation style. Fixing all these issues in the benchmarks can lead to a better performance for Python code generation but not a significant improvement was observed for Java code generation. We also found evidence that GPT-3.5-Turbo and CodeGen-2.5 models may have data contamination issues.
