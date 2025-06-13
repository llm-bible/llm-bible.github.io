---
layout: publication
title: 'Cascading Large Language Models For Salient Event Graph Generation'
authors: Xingwei Tan, Yuxiang Zhou, Gabriele Pergola, Yulan He
conference: "Arxiv"
year: 2024
bibkey: tan2024cascading
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.18449'}
tags: ['RAG', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Prompting', 'Pretraining Methods']
---
Generating event graphs from long documents is challenging due to the
inherent complexity of multiple tasks involved such as detecting events,
identifying their relationships, and reconciling unstructured input with
structured graphs. Recent studies typically consider all events with equal
importance, failing to distinguish salient events crucial for understanding
narratives. This paper presents CALLMSAE, a CAscading Large Language Model
framework for SAlient Event graph generation, which leverages the capabilities
of LLMs and eliminates the need for costly human annotations. We first identify
salient events by prompting LLMs to generate summaries, from which salient
events are identified. Next, we develop an iterative code refinement prompting
strategy to generate event relation graphs, removing hallucinated relations and
recovering missing edges. Powered by CALLMSAE, we present \textit\{NYT-SEG\}, a
large-scale automatically annotated event graph dataset which can serve as
distant supervision signals. Fine-tuning contextualised graph generation models
on \textit\{NYT-SEG\} outperforms the models trained on CAEVO data. Results on a
human-annotated test set show that the proposed method generates salient and
more accurate graphs, outperforming competitive baselines.
