---
layout: publication
title: 'Guided Code Generation With Llms: A Multi-agent Framework For Complex Code Tasks'
authors: Amr Almorsi, Mohanned Ahmed, Walid Gomaa
conference: "Proceedings of the 2024 IEEE International Japan-Africa Conference on Electronics communications and Computations (JAC ECC)"
year: 2025
bibkey: almorsi2025guided
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.06625"}
tags: ['Agentic', 'RAG', 'Applications', 'Tools']
---
Large Language Models (LLMs) have shown remarkable capabilities in code
generation tasks, yet they face significant limitations in handling complex,
long-context programming challenges and demonstrating complex compositional
reasoning abilities. This paper introduces a novel agentic framework for
``guided code generation'' that tries to address these limitations through a
deliberately structured, fine-grained approach to code generation tasks. Our
framework leverages LLMs' strengths as fuzzy searchers and approximate
information retrievers while mitigating their weaknesses in long sequential
reasoning and long-context understanding. Empirical evaluation using OpenAI's
HumanEval benchmark with Meta's Llama 3.1 8B model (int4 precision)
demonstrates a 23.79% improvement in solution accuracy compared to direct
one-shot generation. Our results indicate that structured, guided approaches to
code generation can significantly enhance the practical utility of LLMs in
software development while overcoming their inherent limitations in
compositional reasoning and context handling.
