---
layout: publication
title: 'Do We Need A Detailed Rubric For Automated Essay Scoring Using Large Language Models?'
authors: Lui Yoshida
conference: "Arxiv"
year: 2025
bibkey: yoshida2025do
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.01035'}
tags: ['GPT', 'Applications', 'Model Architecture']
---
This study investigates the necessity and impact of a detailed rubric in
automated essay scoring (AES) using large language models (LLMs). While using
rubrics are standard in LLM-based AES, creating detailed rubrics requires
substantial ef-fort and increases token usage. We examined how different levels
of rubric detail affect scoring accuracy across multiple LLMs using the TOEFL11
dataset. Our experiments compared three conditions: a full rubric, a simplified
rubric, and no rubric, using four different LLMs (Claude 3.5 Haiku, Gemini 1.5
Flash, GPT-4o-mini, and Llama 3 70B Instruct). Results showed that three out of
four models maintained similar scoring accuracy with the simplified rubric
compared to the detailed one, while significantly reducing token usage.
However, one model (Gemini 1.5 Flash) showed decreased performance with more
detailed rubrics. The findings suggest that simplified rubrics may be
sufficient for most LLM-based AES applications, offering a more efficient
alternative without compromis-ing scoring accuracy. However, model-specific
evaluation remains crucial as per-formance patterns vary across different LLMs.
