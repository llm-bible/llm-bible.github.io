---
layout: publication
title: 'Codescholar: Growing Idiomatic Code Examples'
authors: Manish Shetty, Koushik Sen, Ion Stoica
conference: "Arxiv"
year: 2023
bibkey: shetty2023growing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2312.15157'}
tags: ['GPT', 'Tools', 'Model Architecture']
---
Programmers often search for usage examples for API methods. A tool that
could generate realistic, idiomatic, and contextual usage examples for one or
more APIs would be immensely beneficial to developers. Such a tool would
relieve the need for a deep understanding of the API landscape, augment
existing documentation, and help discover interactions among APIs. We present
CodeScholar, a tool that generates idiomatic code examples demonstrating the
common usage of API methods. It includes a novel neural-guided search technique
over graphs that grows the query APIs into idiomatic code examples. Our user
study demonstrates that in 70% of cases, developers prefer CodeScholar
generated examples over state-of-the-art large language models (LLM) like
GPT3.5. We quantitatively evaluate 60 single and 25 multi-API queries from 6
popular Python libraries and show that across-the-board CodeScholar generates
more realistic, diverse, and concise examples. In addition, we show that
CodeScholar not only helps developers but also LLM-powered programming
assistants generate correct code in a program synthesis setting.
