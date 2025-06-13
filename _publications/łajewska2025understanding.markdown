---
layout: publication
title: 'Understanding And Improving Information Preservation In Prompt Compression For Llms'
authors: Weronika Łajewska, Momchil Hardalov, Laura Aina, Neha Anna John, Hang Su, Lluís Màrquez
conference: "Arxiv"
year: 2025
bibkey: łajewska2025understanding
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.19114'}
tags: ['Model Architecture', 'Tools', 'BERT', 'Prompting', 'Ethics and Bias']
---
Recent advancements in large language models (LLMs) have enabled their
successful application to a broad range of tasks. However, in
information-intensive tasks, the prompt length can grow fast, leading to
increased computational requirements, performance degradation, and induced
biases from irrelevant or redundant information. Recently, various prompt
compression techniques have been introduced to optimize the trade-off between
reducing input length and retaining performance. We propose a holistic
evaluation framework that allows for in-depth analysis of prompt compression
methods. We focus on three key aspects, besides compression ratio: (i)
downstream task performance, (ii) grounding in the input context, and (iii)
information preservation. Through this framework, we investigate
state-of-the-art soft and hard compression methods, showing that they struggle
to preserve key details from the original prompt, limiting their performance on
complex tasks. We demonstrate that modifying soft prompting methods to control
better the granularity of the compressed information can significantly improve
their effectiveness -- up to +23% in downstream task performance, more than +8
BERTScore points in grounding, and 2.7x more entities preserved in compression.
