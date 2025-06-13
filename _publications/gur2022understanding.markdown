---
layout: publication
title: 'Understanding HTML With Large Language Models'
authors: Izzeddin Gur, Ofir Nachum, Yingjie Miao, Mustafa Safdari, Austin Huang, Aakanksha Chowdhery, Sharan Narang, Noah Fiedel, Aleksandra Faust
conference: "Arxiv"
year: 2022
bibkey: gur2022understanding
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2210.03945'}
tags: ['Training Techniques', 'Applications', 'Model Architecture']
---
Large language models (LLMs) have shown exceptional performance on a variety
of natural language tasks. Yet, their capabilities for HTML understanding --
i.e., parsing the raw HTML of a webpage, with applications to automation of
web-based tasks, crawling, and browser-assisted retrieval -- have not been
fully explored. We contribute HTML understanding models (fine-tuned LLMs) and
an in-depth analysis of their capabilities under three tasks: (i) Semantic
Classification of HTML elements, (ii) Description Generation for HTML inputs,
and (iii) Autonomous Web Navigation of HTML pages. While previous work has
developed dedicated architectures and training procedures for HTML
understanding, we show that LLMs pretrained on standard natural language
corpora transfer remarkably well to HTML understanding tasks. For instance,
fine-tuned LLMs are 12% more accurate at semantic classification compared to
models trained exclusively on the task dataset. Moreover, when fine-tuned on
data from the MiniWoB benchmark, LLMs successfully complete 50% more tasks
using 192x less data compared to the previous best supervised model. Out of the
LLMs we evaluate, we show evidence that T5-based models are ideal due to their
bidirectional encoder-decoder architecture. To promote further research on LLMs
for HTML understanding, we create and open-source a large-scale HTML dataset
distilled and auto-labeled from CommonCrawl.
