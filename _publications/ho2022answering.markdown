---
layout: publication
title: 'Wikiwhy: Answering And Explaining Cause-and-effect Questions'
authors: Matthew Ho, Aditya Sharma, Justin Chang, Michael Saxon, Sharon Levy, Yujie Lu, William Yang Wang
conference: "Arxiv"
year: 2022
bibkey: ho2022answering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.12152"}
tags: ['Model Architecture', 'Applications', 'GPT', 'Reinforcement Learning']
---
As large language models (LLMs) grow larger and more sophisticated, assessing
their "reasoning" capabilities in natural language grows more challenging.
Recent question answering (QA) benchmarks that attempt to assess reasoning are
often limited by a narrow scope of covered situations and subject matters. We
introduce WikiWhy, a QA dataset built around a novel auxiliary task: explaining
why an answer is true in natural language. WikiWhy contains over 9,000 "why"
question-answer-rationale triples, grounded on Wikipedia facts across a diverse
set of topics. Each rationale is a set of supporting statements connecting the
question to the answer. WikiWhy serves as a benchmark for the reasoning
capabilities of LLMs because it demands rigorous explicit rationales for each
answer to demonstrate the acquisition of implicit commonsense knowledge, which
is unlikely to be easily memorized. GPT-3 baselines achieve only 38.7%
human-evaluated correctness in the end-to-end answer & explain condition,
leaving significant room for future improvements.
