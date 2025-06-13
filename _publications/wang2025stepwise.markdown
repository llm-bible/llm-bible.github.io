---
layout: publication
title: 'Stepwise Informativeness Search For Efficient And Effective LLM Reasoning'
authors: Siyuan Wang, Enda Zhao, Zhongyu Wei, Xiang Ren
conference: "Arxiv"
year: 2025
bibkey: wang2025stepwise
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.15335'}
tags: ['Attention Mechanism', 'RAG', 'Model Architecture', 'Tools', 'Prompting', 'Reinforcement Learning']
---
Advances in Large Language Models (LLMs) have significantly improved
multi-step reasoning through generating free-text rationales. However, recent
studies show that LLMs tend to lose focus over the middle of long contexts.
This raises concerns that as reasoning progresses, LLMs may overlook
information in earlier steps when decoding subsequent steps, leading to
generate unreliable and redundant rationales. To address this, we propose
guiding LLMs to generate more accurate and concise step-by-step rationales by
(1) proactively referencing information from underutilized prior steps, and (2)
minimizing redundant information between new and existing steps. We introduce
stepwise informativeness search, an inference-time tree search framework
incorporating two selection heuristics: grounding-guided selection which
prioritizes steps paying higher attention over underutilized steps; and
novelty-guided selection which encourages steps with novel conclusions. During
rationale generation, we use a self-grounding strategy that prompts LLMs to
explicitly reference relevant prior steps to provide premises before deduction
at each step. Experimental results on four reasoning datasets demonstrate that
our approach improves reasoning accuracy by generating higher-quality
rationales with reduced errors and redundancy.
