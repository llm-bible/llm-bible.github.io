---
layout: publication
title: 'Decore: Decoding By Contrasting Retrieval Heads To Mitigate Hallucinations'
authors: Aryo Pradipta Gema, Chen Jin, Ahmed Abdulaal, Tom Diethe, Philip Teare, Beatrice Alex, Pasquale Minervini, Amrutha Saseendran
conference: "Arxiv"
year: 2024
bibkey: gema2024decoding
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.18860'}
tags: ['Attention Mechanism', 'Transformer', 'Training Techniques', 'Applications', 'Model Architecture', 'Pretraining Methods']
---
Large Language Models (LLMs) often hallucinate, producing unfaithful or
factually incorrect outputs by misrepresenting the provided context or
incorrectly recalling internal knowledge. Recent studies have identified
specific attention heads within the Transformer architecture, known as
retrieval heads, responsible for extracting relevant contextual information. We
hypothesise that masking these retrieval heads can induce hallucinations and
that contrasting the outputs of the base LLM and the masked LLM can reduce
hallucinations. To this end, we propose Decoding by Contrasting Retrieval Heads
(DeCoRe), a novel training-free decoding strategy that amplifies information
found in the context and model parameters. DeCoRe mitigates potentially
hallucinated responses by dynamically contrasting the outputs of the base LLM
and the masked LLM, using conditional entropy as a guide. Our extensive
experiments confirm that DeCoRe significantly improves performance on tasks
requiring high contextual faithfulness, such as summarisation (XSum by 18.6%),
instruction following (MemoTrap by 10.9%), and open-book question answering
(NQ-Open by 2.4% and NQ-Swap by 5.5%).
