---
layout: publication
title: 'Echo: A Large Language Model With Temporal Episodic Memory'
authors: Wentao Liu, Ruohua Zhang, Aimin Zhou, Feng Gao, Jiali Liu
conference: "Arxiv"
year: 2025
bibkey: liu2025large
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.16090'}
tags: ['Training Techniques', 'Agentic', 'Applications', 'Tools']
---
Research on large language models (LLMs) has shown remarkable performance in
domains such as mathematics, programming, and literary creation. However, most
studies have focused on semantic memory-based question answering, neglecting
LLMs' potential to handle episodic memory (EM)-related queries. This oversight
has led to suboptimal performance in applications requiring EM, including
emotional companionship, personal AI assistants, and AI teachers. To address
this gap, we introduce Echo, a LLM enhanced with temporal episodic memory. We
propose a Multi-Agent Data Generation Framework that guides the model in
generating multi-turn, complex scenario episodic memory dialogue data
(EM-Train). Temporal information is innovatively incorporated into the LLM
training process, and Echo is trained using the EM-Train. Furthermore, We
develop an EM-Test benchmark specifically designed to evaluate LLMs' episodic
memory capabilities. The EM-Test assesses performance across various time spans
and difficulty levels, providing a comprehensive evaluation of multi-turn
episodic memory dialogues. Our experiments demonstrate that Echo significantly
outperforms state-of-the-art LLMs on EM-Test. Additionally, a qualitative
analysis reveals Echo's potential to exhibit human-like episodic memory
capabilities. We will open-source all datasets, code, and model weights.
