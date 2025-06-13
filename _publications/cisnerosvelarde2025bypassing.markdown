---
layout: publication
title: 'Bypassing Safety Guardrails In Llms Using Humor'
authors: Pedro Cisneros-velarde
conference: "Arxiv"
year: 2025
bibkey: cisnerosvelarde2025bypassing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.06577"}
tags: ['Responsible AI', 'Prompting']
---
In this paper, we show it is possible to bypass the safety guardrails of
large language models (LLMs) through a humorous prompt including the unsafe
request. In particular, our method does not edit the unsafe request and follows
a fixed template -- it is simple to implement and does not need additional LLMs
to craft prompts. Extensive experiments show the effectiveness of our method
across different LLMs. We also show that both removing and adding more humor to
our method can reduce its effectiveness -- excessive humor possibly distracts
the LLM from fulfilling its unsafe request. Thus, we argue that LLM
jailbreaking occurs when there is a proper balance between focus on the unsafe
request and presence of humor.
