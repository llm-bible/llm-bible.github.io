---
layout: publication
title: 'Show, Don''t Tell: Demonstrations Outperform Descriptions For Schema-guided Task-oriented Dialogue'
authors: Raghav Gupta, Harrison Lee, Jeffrey Zhao, Abhinav Rastogi, Yuan Cao, Yonghui Wu
conference: "In Proceedings of the 2022 Conference of the North American Chapter of the Association for Computational Linguistics Human Language Technologies pages 4541-4549 Seattle United States. Association for Computational Linguistics"
year: 2022
bibkey: gupta2022demonstrations
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2204.04327"}
tags: ['RAG', 'Tools', 'Prompting', 'Applications']
---
Building universal dialogue systems that operate across multiple domains/APIs
and generalize to new ones with minimal overhead is a critical challenge.
Recent works have leveraged natural language descriptions of schema elements to
enable such systems; however, descriptions only indirectly convey schema
semantics. In this work, we propose Show, Don't Tell, which prompts seq2seq
models with a labeled example dialogue to show the semantics of schema elements
rather than tell the model through descriptions. While requiring similar effort
from service developers as generating descriptions, we show that using short
examples as schema representations with large language models results in
state-of-the-art performance on two popular dialogue state tracking benchmarks
designed to measure zero-shot generalization - the Schema-Guided Dialogue
dataset and the MultiWOZ leave-one-out benchmark.
