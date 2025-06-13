---
layout: publication
title: 'Enhancing Ethical Explanations Of Large Language Models Through Iterative Symbolic Refinement'
authors: Xin Quan, Marco Valentino, Louise A. Dennis, André Freitas
conference: "Arxiv"
year: 2024
bibkey: quan2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.00745"}
tags: ['Tools', 'Interpretability and Explainability', 'Reinforcement Learning', 'Prompting', 'In-Context Learning']
---
An increasing amount of research in Natural Language Inference (NLI) focuses
on the application and evaluation of Large Language Models (LLMs) and their
reasoning capabilities. Despite their success, however, LLMs are still prone to
factual errors and inconsistencies in their explanations, offering limited
control and interpretability for inference in complex domains. In this paper,
we focus on ethical NLI, investigating how hybrid neuro-symbolic techniques can
enhance the logical validity and alignment of ethical explanations produced by
LLMs. Specifically, we present an abductive-deductive framework named
Logic-Explainer, which integrates LLMs with an external backward-chaining
solver to refine step-wise natural language explanations and jointly verify
their correctness, reduce incompleteness and minimise redundancy. An extensive
empirical analysis demonstrates that Logic-Explainer can improve explanations
generated via in-context learning methods and Chain-of-Thought (CoT) on
challenging ethical NLI tasks, while, at the same time, producing formal proofs
describing and supporting models' reasoning. As ethical NLI requires
commonsense reasoning to identify underlying moral violations, our results
suggest the effectiveness of neuro-symbolic methods for multi-step NLI more
broadly, opening new opportunities to enhance the logical consistency,
reliability, and alignment of LLMs.
