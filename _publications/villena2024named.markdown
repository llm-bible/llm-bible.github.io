---
layout: publication
title: 'Llmner: (zero|few)-shot Named Entity Recognition, Exploiting The Power Of Large Language Models'
authors: Fabián Villena, Luis Miranda, Claudio Aracena
conference: "Arxiv"
year: 2024
bibkey: villena2024named
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.04528'}
tags: ['Few-Shot', 'Prompting', 'In-Context Learning', 'Tools']
---
Large language models (LLMs) allow us to generate high-quality human-like
text. One interesting task in natural language processing (NLP) is named entity
recognition (NER), which seeks to detect mentions of relevant information in
documents. This paper presents llmNER, a Python library for implementing
zero-shot and few-shot NER with LLMs; by providing an easy-to-use interface,
llmNER can compose prompts, query the model, and parse the completion returned
by the LLM. Also, the library enables the user to perform prompt engineering
efficiently by providing a simple interface to test multiple variables. We
validated our software on two NER tasks to show the library's flexibility.
llmNER aims to push the boundaries of in-context learning research by removing
the barrier of the prompting and parsing steps.
