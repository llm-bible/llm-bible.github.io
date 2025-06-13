---
layout: publication
title: 'Large Language Models Know Your Contextual Search Intent: A Prompting Framework For Conversational Search'
authors: Kelong Mao, Zhicheng Dou, Fengran Mo, Jiewen Hou, Haonan Chen, Hongjin Qian
conference: "Arxiv"
year: 2023
bibkey: mao2023large
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2303.06573'}
tags: ['Language Modeling', 'RAG', 'Security', 'Applications', 'Tools', 'Prompting']
---
Precisely understanding users' contextual search intent has been an important
challenge for conversational search. As conversational search sessions are much
more diverse and long-tailed, existing methods trained on limited data still
show unsatisfactory effectiveness and robustness to handle real conversational
search scenarios. Recently, large language models (LLMs) have demonstrated
amazing capabilities for text generation and conversation understanding. In
this work, we present a simple yet effective prompting framework, called
LLM4CS, to leverage LLMs as a text-based search intent interpreter to help
conversational search. Under this framework, we explore three prompting methods
to generate multiple query rewrites and hypothetical responses, and propose to
aggregate them into an integrated representation that can robustly represent
the user's real contextual search intent. Extensive automatic evaluations and
human evaluations on three widely used conversational search benchmarks,
including CAsT-19, CAsT-20, and CAsT-21, demonstrate the remarkable performance
of our simple LLM4CS framework compared with existing methods and even using
human rewrites. Our findings provide important evidence to better understand
and leverage LLMs for conversational search.
