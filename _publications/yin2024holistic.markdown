---
layout: publication
title: 'MMAU: A Holistic Benchmark Of Agent Capabilities Across Diverse Domains'
authors: Guoli Yin, Haoping Bai, Shuang Ma, Feng Nan, Yanchao Sun, Zhaoyang Xu, Shen Ma, Jiarui Lu, Xiang Kong, Aonan Zhang, Dian Ang Yap, Yizhe Zhang, Karsten Ahnert, Vik Kamath, Mathias Berglund, Dominic Walsh, Tobias Gindele, Juergen Wiest, Zhengfeng Lai, Xiaoming Wang, Jiulong Shan, Meng Cao, Ruoming Pang, Zirui Wang
conference: "Arxiv"
year: 2024
bibkey: yin2024holistic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.18961"}
  - {name: "Code", url: "https://github.com/apple/axlearn/tree/main/docs/research/mmau"}
tags: ['Agentic', 'Tools', 'Reinforcement Learning', 'Has Code', 'Interpretability and Explainability', 'Prompting']
---
Recent advances in large language models (LLMs) have increased the demand for
comprehensive benchmarks to evaluate their capabilities as human-like agents.
Existing benchmarks, while useful, often focus on specific application
scenarios, emphasizing task completion but failing to dissect the underlying
skills that drive these outcomes. This lack of granularity makes it difficult
to deeply discern where failures stem from. Additionally, setting up these
environments requires considerable effort, and issues of unreliability and
reproducibility sometimes arise, especially in interactive tasks. To address
these limitations, we introduce the Massive Multitask Agent Understanding
(MMAU) benchmark, featuring comprehensive offline tasks that eliminate the need
for complex environment setups. It evaluates models across five domains,
including Tool-use, Directed Acyclic Graph (DAG) QA, Data Science and Machine
Learning coding, Contest-level programming and Mathematics, and covers five
essential capabilities: Understanding, Reasoning, Planning, Problem-solving,
and Self-correction. With a total of 20 meticulously designed tasks
encompassing over 3K distinct prompts, MMAU provides a comprehensive framework
for evaluating the strengths and limitations of LLM agents. By testing 18
representative models on MMAU, we provide deep and insightful analyses.
Ultimately, MMAU not only sheds light on the capabilities and limitations of
LLM agents but also enhances the interpretability of their performance.
Datasets and evaluation scripts of MMAU are released at
https://github.com/apple/axlearn/tree/main/docs/research/mmau.
