---
layout: publication
title: Conciseness\: An Overlooked Language Task
authors: Stahlberg Felix, Kumar Aashish, Alberti Chris, Kumar Shankar
conference: "Arxiv"
year: 2022
bibkey: stahlberg2022overlooked
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2211.04126"}
tags: ['Applications', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
We report on novel investigations into training models that make sentences concise. We define the task and show that it is different from related tasks such as summarization and simplification. For evaluation we release two test sets consisting of 2000 sentences each that were annotated by two and five human annotators respectively. We demonstrate that conciseness is a difficult task for which zero-shot setups with large neural language models often do not perform well. Given the limitations of these approaches we propose a synthetic data generation method based on round-trip translations. Using this data to either train Transformers from scratch or fine-tune T5 models yields our strongest baselines that can be further improved by fine-tuning on an artificial conciseness dataset that we derived from multi-annotator machine translation test sets.
