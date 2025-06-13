---
layout: publication
title: 'HEMA : A Hippocampus-inspired Extended Memory Architecture For Long-context AI Conversations'
authors: Kwangseob Ahn
conference: "Arxiv"
year: 2025
bibkey: ahn2025hema
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.16754'}
tags: ['Transformer', 'Efficiency and Optimization', 'Training Techniques', 'Applications', 'Model Architecture', 'Prompting', 'Pruning', 'Reinforcement Learning', 'Pretraining Methods']
---
Large language models (LLMs) struggle with maintaining coherence in extended
conversations spanning hundreds of turns, despite performing well within their
context windows. This paper introduces HEMA (Hippocampus-Inspired Extended
Memory Architecture), a dual-memory system inspired by human cognitive
processes. HEMA combines Compact Memory - a continuously updated one-sentence
summary preserving global narrative coherence, and Vector Memory - an episodic
store of chunk embeddings queried via cosine similarity. When integrated with a
6B-parameter transformer, HEMA maintains coherent dialogues beyond 300 turns
while keeping prompt length under 3,500 tokens. Experimental results show
substantial improvements: factual recall accuracy increases from 41% to 87%,
and human-rated coherence improves from 2.7 to 4.3 on a 5-point scale. With 10K
indexed chunks, Vector Memory achieves P@5 >= 0.80 and R@50 >= 0.74, doubling
the area under the precision-recall curve compared to summarization-only
approaches. Ablation studies reveal two key insights: semantic forgetting
through age-weighted pruning reduces retrieval latency by 34% with minimal
recall loss, and a two-level summary hierarchy prevents cascade errors in
ultra-long conversations exceeding 1,000 turns. HEMA demonstrates that
combining verbatim recall with semantic continuity provides a practical
solution for privacy-aware conversational AI capable of month-long dialogues
without model retraining.
