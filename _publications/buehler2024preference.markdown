---
layout: publication
title: 'Preflexor: Preference-based Recursive Language Modeling For Exploratory Optimization Of Reasoning And Agentic Thinking'
authors: Markus J. Buehler
conference: "Arxiv"
year: 2024
bibkey: buehler2024preference
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.12375"}
tags: ['Fine-Tuning', 'Agentic', 'Efficiency and Optimization', 'Tools', 'Applications', 'Language Modeling', 'Reinforcement Learning', 'Training Techniques']
---
PRefLexOR (Preference-based Recursive Language Modeling for Exploratory
Optimization of Reasoning) combines preference optimization with concepts from
Reinforcement Learning to enable models to self-teach through iterative
reasoning improvements. We propose a recursive learning approach that engages
the model in multi-step reasoning, revisiting, and refining intermediate steps
before producing a final output in training and inference phases. Through
multiple training stages, the model first learns to align its reasoning with
accurate decision paths by optimizing the log odds between preferred and
non-preferred responses. During this process, PRefLexOR builds a dynamic
knowledge graph by generating questions from random text chunks and
retrieval-augmentation to contextualize relevant details from the entire
training corpus. In the second stage, preference optimization enhances model
performance by using rejection sampling to fine-tune reasoning quality by
continually producing in-situ training data while masking the reasoning steps.
Recursive optimization within a thinking token framework introduces iterative
feedback loops, where the model refines reasoning, achieving deeper coherence,
consistency, and adaptability. Implemented in small language models with only 3
billion parameters, we should that even tiny models can iteratively teach
themselves to reason with greater depth and reflectivity. Our implementation is
straightforward and can be incorporated into any existing pretrained LLM. We
focus our examples on applications in biological materials science and
demonstrate the method in a variety of case studies that range from in-domain
to cross-domain applications. Using reasoning strategies that include thinking
and reflection modalities we build a multi-agent recursive self-improving
inference approach to successively improve responses via repeated sampling in
inference time.
