---
layout: publication
title: 'Improving Tool Retrieval By Leveraging Large Language Models For Query Generation'
authors: Mohammad Kachuee, Sarthak Ahuja, Vaibhav Kumar, Puyang Xu, Xiaohu Liu
conference: "COLING 2025"
year: 2024
bibkey: kachuee2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.03573"}
tags: ['Fine-Tuning', 'Tools', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Prompting', 'In-Context Learning']
---
Using tools by Large Language Models (LLMs) is a promising avenue to extend
their reach beyond language or conversational settings. The number of tools can
scale to thousands as they enable accessing sensory information, fetching
updated factual knowledge, or taking actions in the real world. In such
settings, in-context learning by providing a short list of relevant tools in
the prompt is a viable approach. To retrieve relevant tools, various approaches
have been suggested, ranging from simple frequency-based matching to dense
embedding-based semantic retrieval. However, such approaches lack the
contextual and common-sense understanding required to retrieve the right tools
for complex user requests. Rather than increasing the complexity of the
retrieval component itself, we propose leveraging LLM understanding to generate
a retrieval query. Then, the generated query is embedded and used to find the
most relevant tools via a nearest-neighbor search. We investigate three
approaches for query generation: zero-shot prompting, supervised fine-tuning on
tool descriptions, and alignment learning by iteratively optimizing a reward
metric measuring retrieval performance. By conducting extensive experiments on
a dataset covering complex and multi-tool scenarios, we show that leveraging
LLMs for query generation improves the retrieval for in-domain (seen tools) and
out-of-domain (unseen tools) settings.
