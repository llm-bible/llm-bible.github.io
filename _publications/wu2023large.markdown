---
layout: publication
title: 'Large Language Models Should Ask Clarifying Questions To Increase Confidence In Generated Code'
authors: Jie Jw Wu
conference: "Arxiv"
year: 2023
bibkey: wu2023large
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2308.13507'}
tags: ['RAG', 'Applications']
---
Large language models (LLMs) have significantly improved the ability to
perform tasks in the field of code generation. However, there is still a gap
between LLMs being capable coders and being top-tier software engineers. Based
on the observation that toplevel software engineers often ask clarifying
questions to reduce ambiguity in both requirements and coding solutions, I
argue that the same should be applied to LLMs for code generation tasks. By
asking probing questions in various topics before generating the final code,
the challenges of programming with LLMs, such as unclear intent specification,
lack of computational thinking, and undesired code quality, may be alleviated.
This, in turn, increases confidence in the generated code. In this work, I
explore how to leverage better communication skills to achieve greater
confidence in generated code. I propose a communication-centered process that
uses an LLM-generated communicator to identify issues with high ambiguity or
low confidence in problem descriptions and generated code. I then ask
clarifying questions to obtain responses from users for refining the code.
