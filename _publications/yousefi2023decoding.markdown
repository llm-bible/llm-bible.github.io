---
layout: publication
title: 'Decoding In-context Learning: Neuroscience-inspired Analysis Of Representations In Large Language Models'
authors: Yousefi Safoora, Betthauser Leo, Hasanbeig Hosein, Millière Raphaël, Momennejad Ida
conference: "Arxiv"
year: 2023
bibkey: yousefi2023decoding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.00313"}
tags: ['Applications', 'Attention Mechanism', 'In Context Learning', 'Model Architecture', 'Prompting', 'RAG', 'Tools']
---
Large language models (LLMs) exhibit remarkable performance improvement
through in-context learning (ICL) by leveraging task-specific examples in the
input. However, the mechanisms behind this improvement remain elusive. In this
work, we investigate how LLM embeddings and attention representations change
following in-context-learning, and how these changes mediate improvement in
behavior. We employ neuroscience-inspired techniques such as representational
similarity analysis (RSA) and propose novel methods for parameterized probing
and measuring ratio of attention to relevant vs. irrelevant information in
Llama-2 70B and Vicuna 13B. We designed two tasks with a priori relationships
among their conditions: linear regression and reading comprehension. We formed
hypotheses about expected similarities in task representations and measured
hypothesis alignment of LLM representations before and after ICL as well as
changes in attention. Our analyses revealed a meaningful correlation between
improvements in behavior after ICL and changes in both embeddings and attention
weights across LLM layers. This empirical framework empowers a nuanced
understanding of how latent representations shape LLM behavior, offering
valuable tools and insights for future research and practical applications.
