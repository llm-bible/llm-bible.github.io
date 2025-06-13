---
layout: publication
title: 'Largepig: Your Large Language Model Is Secretly A Pointer Generator'
authors: Zhongxiang Sun, Zihua Si, Xiaoxue Zang, Kai Zheng, Yang Song, Xiao Zhang, Jun Xu
conference: "Arxiv"
year: 2024
bibkey: sun2024your
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.11366"}
tags: ['RAG', 'Training Techniques', 'Attention Mechanism', 'Model Architecture']
---
Recent research on query generation has focused on using Large Language
Models (LLMs), which despite bringing state-of-the-art performance, also
introduce issues with hallucinations in the generated queries. In this work, we
introduce relevance hallucination and factuality hallucination as a new
typology for hallucination problems brought by query generation based on LLMs.
We propose an effective way to separate content from form in LLM-generated
queries, which preserves the factual knowledge extracted and integrated from
the inputs and compiles the syntactic structure, including function words,
using the powerful linguistic capabilities of the LLM. Specifically, we
introduce a model-agnostic and training-free method that turns the Large
Language Model into a Pointer-Generator (LargePiG), where the pointer attention
distribution leverages the LLM's inherent attention weights, and the copy
probability is derived from the difference between the vocabulary distribution
of the model's high layers and the last layer. To validate the effectiveness of
LargePiG, we constructed two datasets for assessing the hallucination problems
in query generation, covering both document and video scenarios. Empirical
studies on various LLMs demonstrated the superiority of LargePiG on both
datasets. Additional experiments also verified that LargePiG could reduce
hallucination in large vision language models and improve the accuracy of
document-based question-answering and factuality evaluation tasks.
