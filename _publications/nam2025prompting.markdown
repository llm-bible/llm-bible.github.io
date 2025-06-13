---
layout: publication
title: 'Prompting Llms For Code Editing: Struggles And Remedies'
authors: Daye Nam, Ahmed Omran, Ambar Murillo, Saksham Thakur, Abner Araujo, Marcel Blistein, Alexander Frömmgen, Vincent Hellendoorn, Satish Chandra
conference: "Arxiv"
year: 2025
bibkey: nam2025prompting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.20196"}
tags: ['Tools', 'Prompting']
---
Large Language Models (LLMs) are rapidly transforming software engineering,
with coding assistants embedded in an IDE becoming increasingly prevalent.
While research has focused on improving the tools and understanding developer
perceptions, a critical gap exists in understanding how developers actually use
these tools in their daily workflows, and, crucially, where they struggle. This
paper addresses part of this gap through a multi-phased investigation of
developer interactions with an LLM-powered code editing and transformation
feature, Transform Code, in an IDE widely used at Google. First, we analyze
telemetry logs of the feature usage, revealing that frequent re-prompting can
be an indicator of developer struggles with using Transform Code. Second, we
conduct a qualitative analysis of unsatisfactory requests, identifying five key
categories of information often missing from developer prompts. Finally, based
on these findings, we propose and evaluate a tool, AutoPrompter, for
automatically improving prompts by inferring missing information from the
surrounding code context, leading to a 27% improvement in edit correctness on
our test set.
