---
layout: publication
title: 'Reconstructing Context: Evaluating Advanced Chunking Strategies For Retrieval-augmented Generation'
authors: Carlo Merola, Jaspinder Singh
conference: "Arxiv"
year: 2025
bibkey: merola2025reconstructing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.19754'}
tags: ['RAG', 'Efficiency and Optimization']
---
Retrieval-augmented generation (RAG) has become a transformative approach for
enhancing large language models (LLMs) by grounding their outputs in external
knowledge sources. Yet, a critical question persists: how can vast volumes of
external knowledge be managed effectively within the input constraints of LLMs?
Traditional methods address this by chunking external documents into smaller,
fixed-size segments. While this approach alleviates input limitations, it often
fragments context, resulting in incomplete retrieval and diminished coherence
in generation. To overcome these shortcomings, two advanced techniques, late
chunking and contextual retrieval, have been introduced, both aiming to
preserve global context. Despite their potential, their comparative strengths
and limitations remain unclear. This study presents a rigorous analysis of late
chunking and contextual retrieval, evaluating their effectiveness and
efficiency in optimizing RAG systems. Our results indicate that contextual
retrieval preserves semantic coherence more effectively but requires greater
computational resources. In contrast, late chunking offers higher efficiency
but tends to sacrifice relevance and completeness.
