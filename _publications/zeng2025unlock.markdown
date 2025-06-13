---
layout: publication
title: 'Fineedit: Unlock Instruction-based Text Editing For Llms'
authors: Yiming Zeng, Wanhao Yu, Zexin Li, Tao Ren, Yu Ma, Jinghan Cao, Xiyan Chen, Tingting Yu
conference: "Arxiv"
year: 2025
bibkey: zeng2025unlock
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.13358"}
tags: ['Model Architecture', 'Reinforcement Learning', 'Language Modeling', 'Applications', 'Attention Mechanism']
---
Large Language Models (LLMs) have significantly advanced natural language processing, demonstrating strong capabilities in tasks such as text generation, summarization, and reasoning. Recently, their potential for automating precise text editing tasks across specialized domains, such as programming code, LaTeX, and structured database languages, has gained attention. However, current state-of-the-art LLMs still struggle with executing precise, instruction-driven edits, particularly when structural accuracy and strict adherence to domain conventions are required. To address these challenges, we introduce InstrEditBench, an automated benchmark dataset comprising over 30,000 structured editing tasks spanning diverse domains, including Wikipedia articles, LaTeX documents, source code, and database languages. Using this benchmark, we develop FineEdit, a specialized editing model explicitly trained for accurate, context-aware text modifications. Experimental evaluations demonstrate that FineEdit outperforms state-of-the-art models, achieving improvements of approximately 10% over Gemini models on single-turn edits, up to 30% over Llama-3.2-3B, and exceeding Mistral-7B-OpenOrca performance by over 40% on direct editing tasks. FineEdit also effectively generalizes to realistic multi-turn editing scenarios, highlighting its practical applicability.
