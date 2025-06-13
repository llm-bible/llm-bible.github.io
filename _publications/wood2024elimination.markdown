---
layout: publication
title: '100% Elimination Of Hallucinations On Ragtruth For GPT-4 And GPT-3.5 Turbo'
authors: Michael C. Wood, Adam A. Forbes
conference: "Arxiv"
year: 2024
bibkey: wood2024elimination
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.05223'}
tags: ['RAG', 'GPT', 'Applications', 'Model Architecture']
---
The issue of hallucinations in large language models (LLMs) remains a
critical barrier to the adoption of AI in enterprise and other high-stakes
applications. Despite advancements in retrieval-augmented generation (RAG)
systems, current state-of-the-art methods fail to achieve more than 80%
accuracy in generating faithful and factually correct outputs, even when
provided with relevant and accurate context. In this work, we introduce Acurai,
a novel systematic approach that achieves 100% hallucination-free responses in
LLMs by reformatting queries and context data prior to input. Leveraging a deep
understanding of LLM internal representations, the importance of noun-phrase
dominance, and the role of discrete functional units (DFUs), Acurai ensures
alignment between input context and generated output. We validate this method
using the RAGTruth corpus, demonstrating its ability to eliminate 100%
hallucinations for both GPT-4 and GPT-3.5 Turbo. Acurai sets a new standard for
achieving consistent, accurate, and faithful AI responses, marking a
significant step forward in the development of trustworthy AI systems.
