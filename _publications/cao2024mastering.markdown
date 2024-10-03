---
layout: publication
title: 'Tonggu: Mastering Classical Chinese Understanding With Knowledge-grounded Large Language Models'
authors: Cao Jiahuan, Peng Dezhi, Zhang Peirong, Shi Yongxin, Liu Yang, Ding Kai, Jin Lianwen
conference: "Arxiv"
year: 2024
bibkey: cao2024mastering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.03937"}
tags: ['Fine Tuning', 'RAG']
---
Classical Chinese is a gateway to the rich heritage and wisdom of ancient China, yet its complexities pose formidable comprehension barriers for most modern people without specialized knowledge. While Large Language Models (LLMs) have shown remarkable capabilities in Natural Language Processing (NLP), they struggle with Classical Chinese Understanding (CCU), especially in data-demanding and knowledge-intensive tasks. In response to this dilemma, we propose \textbf\{TongGu\} (mean understanding ancient and modern), the first CCU-specific LLM, underpinned by three core contributions. First, we construct a two-stage instruction-tuning dataset ACCN-INS derived from rich classical Chinese corpora, aiming to unlock the full CCU potential of LLMs. Second, we propose Redundancy-Aware Tuning (RAT) to prevent catastrophic forgetting, enabling TongGu to acquire new capabilities while preserving its foundational knowledge. Third, we present a CCU Retrieval-Augmented Generation (CCU-RAG) technique to reduce hallucinations based on knowledge-grounding. Extensive experiments across 24 diverse CCU tasks validate TongGu's superior ability, underscoring the effectiveness of RAT and CCU-RAG. The model and dataset will be public available.
