---
layout: publication
title: 'Structured Prompting And Feedback-guided Reasoning With Llms For Data Interpretation'
authors: Amit Rath
conference: "Arxiv"
year: 2025
bibkey: rath2025structured
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.01636'}
tags: ['Agentic', 'Interpretability and Explainability', 'RAG', 'Tools', 'Applications', 'Fine-Tuning', 'Prompting']
---
Large language models (LLMs) have demonstrated remarkable capabilities in
natural language understanding and task generalization. However, their
application to structured data analysis remains fragile due to inconsistencies
in schema interpretation, misalignment between user intent and model output,
and limited mechanisms for self-correction when failures occur. This paper
introduces the STROT Framework (Structured Task Reasoning and Output
Transformation), a method for structured prompting and feedback-driven
transformation logic generation aimed at improving the reliability and semantic
alignment of LLM-based analytical workflows. STROT begins with lightweight
schema introspection and sample-based field classification, enabling dynamic
context construction that captures both the structure and statistical profile
of the input data. This contextual information is embedded in structured
prompts that guide the model toward generating task-specific, interpretable
outputs. To address common failure modes in complex queries, STROT incorporates
a refinement mechanism in which the model iteratively revises its outputs based
on execution feedback and validation signals. Unlike conventional approaches
that rely on static prompts or single-shot inference, STROT treats the LLM as a
reasoning agent embedded within a controlled analysis loop -- capable of
adjusting its output trajectory through planning and correction. The result is
a robust and reproducible framework for reasoning over structured data with
LLMs, applicable to diverse data exploration and analysis tasks where
interpretability, stability, and correctness are essential.
