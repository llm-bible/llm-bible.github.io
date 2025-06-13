---
layout: publication
title: 'DOCBENCH: A Benchmark For Evaluating Llm-based Document Reading Systems'
authors: Anni Zou, Wenhao Yu, Hongming Zhang, Kaixin Ma, Deng Cai, Zhuosheng Zhang, Hai Zhao, Dong Yu
conference: "Arxiv"
year: 2024
bibkey: zou2024benchmark
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.10701"}
tags: ['Tools', 'Reinforcement Learning']
---
Recently, there has been a growing interest among large language model (LLM)
developers in LLM-based document reading systems, which enable users to upload
their own documents and pose questions related to the document contents, going
beyond simple reading comprehension tasks. Consequently, these systems have
been carefully designed to tackle challenges such as file parsing, metadata
extraction, multi-modal information understanding and long-context reading.
However, no current benchmark exists to evaluate their performance in such
scenarios, where a raw file and questions are provided as input, and a
corresponding response is expected as output. In this paper, we introduce
DocBench, a new benchmark designed to evaluate LLM-based document reading
systems. Our benchmark involves a meticulously crafted process, including the
recruitment of human annotators and the generation of synthetic questions. It
includes 229 real documents and 1,102 questions, spanning across five different
domains and four major types of questions. We evaluate both proprietary
LLM-based systems accessible via web interfaces or APIs, and a parse-then-read
pipeline employing open-source LLMs. Our evaluations reveal noticeable gaps
between existing LLM-based document reading systems and human performance,
underscoring the challenges of developing proficient systems. To summarize,
DocBench aims to establish a standardized benchmark for evaluating LLM-based
document reading systems under diverse real-world scenarios, thereby guiding
future advancements in this research area.
