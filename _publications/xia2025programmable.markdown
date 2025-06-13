---
layout: publication
title: 'Minerva: A Programmable Memory Test Benchmark For Language Models'
authors: Menglin Xia, Victor Ruehle, Saravan Rajmohan, Reza Shokri
conference: "Arxiv"
year: 2025
bibkey: xia2025programmable
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.03358'}
tags: ['Reinforcement Learning', 'Tools']
---
How effectively can LLM-based AI assistants utilize their memory (context) to
perform various tasks? Traditional data benchmarks, which are often manually
crafted, suffer from several limitations: they are static, susceptible to
overfitting, difficult to interpret, and lack actionable insights--failing to
pinpoint the specific capabilities a model lacks when it does not pass a test.
In this paper, we present a framework for automatically generating a
comprehensive set of tests to evaluate models' abilities to use their memory
effectively. Our framework extends the range of capability tests beyond the
commonly explored (passkey, key-value, needle in the haystack) search, a
dominant focus in the literature. Specifically, we evaluate models on atomic
tasks such as searching, recalling, editing, matching, comparing information in
context memory, and performing basic operations when inputs are structured into
distinct blocks, simulating real-world data. Additionally, we design composite
tests to investigate the models' ability to maintain state while operating on
memory. Our benchmark enables an interpretable, detailed assessment of memory
capabilities of LLMs.
