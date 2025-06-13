---
layout: publication
title: 'Livemind: Low-latency Large Language Models With Simultaneous Inference'
authors: Chuangtao Chen, Grace Li Zhang, Xunzhao Yin, Cheng Zhuo, Ulf Schlichtmann, Bing Li
conference: "Arxiv"
year: 2024
bibkey: chen2024low
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.14319"}
tags: ['RAG', 'Tools']
---
In this paper, we introduce LiveMind, a novel low-latency inference framework
for large language model (LLM) inference which enables LLMs to perform
inferences with incomplete user input. By reallocating computational processes
to the input phase, a substantial reduction in latency is achieved, thereby
significantly enhancing the interactive experience for users of LLMs. The
framework adeptly manages the visibility of the streaming input to the model,
allowing it to infer from incomplete user input or await additional content.
Compared with traditional inference methods on complete user input, our
approach demonstrates an average reduction in response latency of 84.0% on the
MMLU dataset and 71.6% on the MMLU-Pro dataset, while maintaining comparable
accuracy. Additionally, our framework facilitates collaborative inference and
output across different models. By employing an large LLM for inference and a
small LLM for output, we achieve an average 37% reduction in response latency,
alongside a 4.30% improvement in accuracy on the MMLU-Pro dataset compared with
the baseline. The proposed LiveMind framework advances the field of human-AI
interaction by enabling more responsive and efficient communication between
users and AI systems.
