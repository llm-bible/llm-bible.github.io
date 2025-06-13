---
layout: publication
title: 'Memhunter: Automated And Verifiable Memorization Detection At Dataset-scale In Llms'
authors: Zhenpeng Wu, Jian Lou, Zibin Zheng, Chuan Chen
conference: "Arxiv"
year: 2024
bibkey: wu2024automated
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.07261'}
tags: ['Reinforcement Learning', 'Prompting', 'Training Techniques']
---
Large language models (LLMs) have been shown to memorize and reproduce
content from their training data, raising significant privacy concerns,
especially with web-scale datasets. Existing methods for detecting memorization
are primarily sample-specific, relying on manually crafted or discretely
optimized memory-inducing prompts generated on a per-sample basis, which become
impractical for dataset-level detection due to the prohibitive computational
cost of iterating through all samples. In real-world scenarios, data owners may
need to verify whether a susceptible LLM has memorized their dataset,
particularly if the LLM may have collected the data from the web without
authorization. To address this, we introduce MemHunter, which trains a
memory-inducing LLM and employs hypothesis testing to efficiently detect
memorization at the dataset level, without requiring sample-specific memory
inducing. Experiments on models like Pythia and Llama demonstrate that
MemHunter can extract up to 40% more training data than existing methods under
constrained time resources and reduce search time by up to 80% when integrated
as a plug-in. Crucially, MemHunter is the first method capable of dataset-level
memorization detection, providing a critical tool for assessing privacy risks
in LLMs powered by large-scale datasets.
