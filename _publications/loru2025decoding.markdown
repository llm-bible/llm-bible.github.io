---
layout: publication
title: 'Decoding AI Judgment: How Llms Assess News Credibility And Bias'
authors: Edoardo Loru, Jacopo Nudo, Niccolò Di Marco, Matteo Cinelli, Walter Quattrociocchi
conference: "Arxiv"
year: 2025
bibkey: loru2025decoding
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.04426'}
tags: ['Ethics and Bias', 'Model Architecture', 'Tools', 'GPT']
---
Large Language Models (LLMs) are increasingly used to assess news
credibility, yet little is known about how they make these judgments. While
prior research has examined political bias in LLM outputs or their potential
for automated fact-checking, their internal evaluation processes remain largely
unexamined. Understanding how LLMs assess credibility provides insights into AI
behavior and how credibility is structured and applied in large-scale language
models. This study benchmarks the reliability and political classifications of
state-of-the-art LLMs - Gemini 1.5 Flash (Google), GPT-4o mini (OpenAI), and
LLaMA 3.1 (Meta) - against structured, expert-driven rating systems such as
NewsGuard and Media Bias Fact Check. Beyond assessing classification
performance, we analyze the linguistic markers that shape LLM decisions,
identifying which words and concepts drive their evaluations. We uncover
patterns in how LLMs associate credibility with specific linguistic features by
examining keyword frequency, contextual determinants, and rank distributions.
Beyond static classification, we introduce a framework in which LLMs refine
their credibility assessments by retrieving external information, querying
other models, and adapting their responses. This allows us to investigate
whether their assessments reflect structured reasoning or rely primarily on
prior learned associations.
