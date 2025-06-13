---
layout: publication
title: 'A Comprehensive Framework For Evaluating Api-oriented Code Generation In Large Language Models'
authors: Yixi Wu, Pengfei He, Zehao Wang, Shaowei Wang, Yuan Tian, Tse-hsun Chen
conference: "Arxiv"
year: 2024
bibkey: wu2024comprehensive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.15228"}
tags: ['Tools', 'GPT', 'Applications', 'RAG', 'Model Architecture']
---
Large language models (LLMs) like GitHub Copilot and ChatGPT have emerged as
powerful tools for code generation, significantly enhancing productivity and
accelerating software development. However, existing benchmarks primarily focus
on general code generation without considering API-oriented code generation,
i.e., generating code that invokes APIs from specific libraries. Given the
growing demand for API-oriented code generation, there is a pressing need for a
systematic and automated approach to evaluate LLM on API-oriented code
generation. To address this gap, we propose AutoAPIEval, a lightweight and
automated framework designed to evaluate the capabilities of LLMs in
API-oriented code generation. Our framework works with any library that
provides API documentation and focuses on two unit tasks: API recommendation
and code example generation, along with four metrics to evaluate the generated
APIs and code examples, such as the proportion of incorrect API recommendations
for Task 1, and the proportion of code examples where no specific API is
invoked and uncompilable/unexecutable code examples for Task 2. In addition, we
conducted a case study on three LLMs (ChatGPT, MagiCoder, and DeepSeek Coder)
and Java Runtime Environment 8 to demonstrate the framework's effectiveness.
Our findings reveal substantial variability in LLM performance across tasks,
with ChatGPT adhering better to instructions, while sharing similar
effectiveness in code example generation with its counterparts (i.e., MagiCoder
and DeekSeek Coder). We also identify key factors associated with code quality,
such as API popularity and model confidence, and build classifiers that achieve
high accuracy in detecting incorrect API recommendations and erroneous code
examples. Retrieval-augmented generation enhances the quality of code generated
by LLMs, though its effectiveness varies across different LLMs.
