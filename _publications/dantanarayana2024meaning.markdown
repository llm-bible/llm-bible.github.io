---
layout: publication
title: 'Meaning-typed Programming: Language Abstraction And Runtime For Model-integrated Applications'
authors: Jayanaka L. Dantanarayana, Yiping Kang, Kugesan Sivasothynathan, Christopher Clarke, Baichuan Li, Savini Kashmira, Krisztian Flautner, Lingjia Tang, Jason Mars
conference: "Arxiv"
year: 2024
bibkey: dantanarayana2024meaning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.08965"}
tags: ['Efficiency and Optimization', 'Tools', 'RAG', 'Prompting', 'Applications']
---
Software development is shifting from traditional logical programming to model-integrated applications that leverage generative AI and large language models (LLMs) during runtime. However, integrating LLMs remains complex, requiring developers to manually craft prompts and process outputs. Existing tools attempt to assist with prompt engineering, but often introduce additional complexity.
  This paper presents Meaning-Typed Programming (MTP) model, a novel paradigm that abstracts LLM integration through intuitive language-level constructs. By leveraging the inherent semantic richness of code, MTP automates prompt generation and response handling without additional developer effort. We introduce the by operator for seamless LLM invocation, MT-IR, a meaning-based intermediate representation for semantic extraction, and MT-Runtime, an automated system for managing LLM interactions. We implement MTP in Jac, a Python superset language and find that MTP significantly reduces coding complexity while maintaining accuracy and efficiency. Our evaluation across diverse benchmarks and user studies demonstrates that MTP outperforms existing frameworks such as DSPy and LMQL by reducing lines of code by factors of 2.3-7.5X and 1.3-10.7X respectively. For math problems from the GSM8k dataset, MTP achieves accuracy rates approaching 90%, while reducing token usage in 10 out of 13 benchmarks. This leads to cost savings up to 4.5X and runtime speedups as high as 4.75X. Additionally, MTP demonstrates resilience even when 50% of naming conventions are suboptimal, establishing it as a practical, efficient solution for streamlining model-integrated application development.
