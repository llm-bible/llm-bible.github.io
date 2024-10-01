---
layout: publication
title: 'Livemind: Low-latency Large Language Models With Simultaneous Inference'
authors: Chen Chuangtao, Zhang Grace Li, Yin Xunzhao, Zhuo Cheng, Schlichtmann Ulf, Li Bing
conference: "Arxiv"
year: 2024
bibkey: chen2024low
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.14319"}
tags: ['Pretraining Methods', 'Prompting', 'RAG', 'Tools']
---
In this paper, we introduce a novel low-latency inference framework for large language models (LLMs) inference which enables LLMs to perform inferences with incomplete prompts. By reallocating computational processes to prompt input phase, we achieve a substantial reduction in latency, thereby significantly enhancing the interactive experience for users of LLMs. The framework adeptly manages the visibility of the streaming prompt to the model, allowing it to infer from incomplete prompts or await additional prompts. Compared with traditional inference methods that utilize complete prompts, our approach demonstrates an average reduction of 59&#37; in response latency on the MMLU-Pro dataset, while maintaining comparable accuracy. Additionally, our framework facilitates collaborative inference and output across different models. By employing an LLM for inference and a small language model (SLM) for output, we achieve an average 68&#37; reduction in response latency, alongside a 5.5&#37; improvement in accuracy on the MMLU-Pro dataset compared with the SLM baseline. For long prompts exceeding 20 sentences, the response latency can be reduced by up to 93&#37;.
