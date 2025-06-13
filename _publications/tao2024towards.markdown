---
layout: publication
title: 'Towards Reliable Detection Of Llm-generated Texts: A Comprehensive Evaluation Framework With CUDRT'
authors: Zhen Tao, Yanfang Chen, Dinghao Xi, Zhiyu Li, Wei Xu
conference: "Arxiv"
year: 2024
bibkey: tao2024towards
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.09056'}
tags: ['Language Modeling', 'Model Architecture', 'Tools', 'Applications', 'Training Techniques', 'Reinforcement Learning']
---
The increasing prevalence of large language models (LLMs) has significantly
advanced text generation, but the human-like quality of LLM outputs presents
major challenges in reliably distinguishing between human-authored and
LLM-generated texts. Existing detection benchmarks are constrained by their
reliance on static datasets, scenario-specific tasks (e.g., question answering
and text refinement), and a primary focus on English, overlooking the diverse
linguistic and operational subtleties of LLMs. To address these gaps, we
propose CUDRT, a comprehensive evaluation framework and bilingual benchmark in
Chinese and English, categorizing LLM activities into five key operations:
Create, Update, Delete, Rewrite, and Translate. CUDRT provides extensive
datasets tailored to each operation, featuring outputs from state-of-the-art
LLMs to assess the reliability of LLM-generated text detectors. This framework
supports scalable, reproducible experiments and enables in-depth analysis of
how operational diversity, multilingual training sets, and LLM architectures
influence detection performance. Our extensive experiments demonstrate the
framework's capacity to optimize detection systems, providing critical insights
to enhance reliability, cross-linguistic adaptability, and detection accuracy.
By advancing robust methodologies for identifying LLM-generated texts, this
work contributes to the development of intelligent systems capable of meeting
real-world multilingual detection challenges. Source code and dataset are
available at GitHub.
