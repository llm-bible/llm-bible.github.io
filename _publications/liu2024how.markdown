---
layout: publication
title: 'How Much Can RAG Help The Reasoning Of LLM?'
authors: Jingyu Liu, Jiaen Lin, Yong Liu
conference: "Arxiv"
year: 2024
bibkey: liu2024how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.02338"}
tags: ['Fine-Tuning', 'Transformer', 'RAG', 'Model Architecture', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Retrieval-Augmented Generation (RAG) has gained significant popularity in
modern Large Language Models (LLMs) due to its effectiveness in introducing new
knowledge and reducing hallucinations. However, the deep understanding of RAG
remains limited, how does RAG help the reasoning process and can RAG help
improve the reasoning capability remains question. While external documents are
typically considered as a method to incorporate domain-specific information,
they also contain intermediate reasoning results related to the query, this
suggests that documents could enhance the reasoning capability of LLMs, which
has not been previously explored. In this paper, we investigate this issue in
depth and find that while RAG can assist with reasoning, the help is limited.
If we conceptualize the reasoning process as a tree with fixed depth, then RAG
struggles to assist LLMs in performing deeper reasoning. Additionally, the
information in the documents requires preprocessing to filter out noise. We
demonstrate that this preprocessing is difficult to achieve simply fine-tuning
of the LLM, it often necessitates numerous additional transformer layers to
solve the problem. To simplify the problem, we propose DPrompt tuning, which
effectively resolves the issue within just limited transformer layers, leading
to improved performance.
