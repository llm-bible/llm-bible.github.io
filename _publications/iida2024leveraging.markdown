---
layout: publication
title: 'CATER: Leveraging LLM To Pioneer A Multidimensional, Reference-independent Paradigm In Translation Quality Evaluation'
authors: Kurando Iida, Kenjiro Mimura
conference: "Arxiv"
year: 2024
bibkey: iida2024leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.11261"}
tags: ['RAG', 'Tools', 'Prompting', 'Reinforcement Learning']
---
This paper introduces the Comprehensive AI-assisted Translation Edit Ratio
(CATER), a novel and fully prompt-driven framework for evaluating machine
translation (MT) quality. Leveraging large language models (LLMs) via a
carefully designed prompt-based protocol, CATER expands beyond traditional
reference-bound metrics, offering a multidimensional, reference-independent
evaluation that addresses linguistic accuracy, semantic fidelity, contextual
coherence, stylistic appropriateness, and information completeness. CATER's
unique advantage lies in its immediate implementability: by providing the
source and target texts along with a standardized prompt, an LLM can rapidly
identify errors, quantify edit effort, and produce category-level and overall
scores. This approach eliminates the need for pre-computed references or
domain-specific resources, enabling instant adaptation to diverse languages,
genres, and user priorities through adjustable weights and prompt
modifications. CATER's LLM-enabled strategy supports more nuanced assessments,
capturing phenomena such as subtle omissions, hallucinations, and
discourse-level shifts that increasingly challenge contemporary MT systems. By
uniting the conceptual rigor of frameworks like MQM and DQF with the
scalability and flexibility of LLM-based evaluation, CATER emerges as a
valuable tool for researchers, developers, and professional translators
worldwide. The framework and example prompts are openly available, encouraging
community-driven refinement and further empirical validation.
