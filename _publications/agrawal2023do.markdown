---
layout: publication
title: 'Do Language Models Know When They''re Hallucinating References?'
authors: Ayush Agrawal, Mirac Suzgun, Lester Mackey, Adam Tauman Kalai
conference: "Arxiv"
year: 2023
bibkey: agrawal2023do
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.18248"}
  - {name: "Code", url: "https://github.com/microsoft/hallucinated-references"}
tags: ['GPT', 'Has Code', 'Model Architecture']
---
State-of-the-art language models (LMs) are notoriously susceptible to
generating hallucinated information. Such inaccurate outputs not only undermine
the reliability of these models but also limit their use and raise serious
concerns about misinformation and propaganda. In this work, we focus on
hallucinated book and article references and present them as the "model
organism" of language model hallucination research, due to their frequent and
easy-to-discern nature. We posit that if a language model cites a particular
reference in its output, then it should ideally possess sufficient information
about its authors and content, among other relevant details. Using this basic
insight, we illustrate that one can identify hallucinated references without
ever consulting any external resources, by asking a set of direct or indirect
queries to the language model about the references. These queries can be
considered as "consistency checks." Our findings highlight that while LMs,
including GPT-4, often produce inconsistent author lists for hallucinated
references, they also often accurately recall the authors of real references.
In this sense, the LM can be said to "know" when it is hallucinating
references. Furthermore, these findings show how hallucinated references can be
dissected to shed light on their nature. Replication code and results can be
found at https://github.com/microsoft/hallucinated-references.
