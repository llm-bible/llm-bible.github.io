---
layout: publication
title: 'Structured Thinking Matters: Improving Llms Generalization In Causal Inference Tasks'
authors: Wentao Sun, João Paulo Nogueira, Alonso Silva
conference: "Arxiv"
year: 2025
bibkey: sun2025structured
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.18034'}
tags: ['Prompting', 'GPT', 'Applications', 'Model Architecture']
---
Despite remarkable advances in the field, LLMs remain unreliable in distinguishing causation from correlation. Recent results from the Corr2Cause dataset benchmark reveal that state-of-the-art LLMs -- such as GPT-4 (F1 score: 29.08) -- only marginally outperform random baselines (Random Uniform, F1 score: 20.38), indicating limited capacity of generalization. To tackle this limitation, we propose a novel structured approach: rather than directly answering causal queries, we provide the model with the capability to structure its thinking by guiding the model to build a structured knowledge graph, systematically encoding the provided correlational premises, to answer the causal queries. This intermediate representation significantly enhances the model's causal capabilities. Experiments on the test subset of the Corr2Cause dataset benchmark with Qwen3-32B model (reasoning model) show substantial gains over standard direct prompting methods, improving F1 scores from 32.71 to 48.26 (over 47.5% relative increase), along with notable improvements in precision and recall. These results underscore the effectiveness of providing the model with the capability to structure its thinking and highlight its promising potential for broader generalization across diverse causal inference tasks.
