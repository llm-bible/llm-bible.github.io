---
layout: publication
title: 'Evaluating Large Language Models For Document-grounded Response Generation In Information-seeking Dialogues'
authors: Norbert Braunschweiler, Rama Doddipatla, Simon Keizer, Svetlana Stoyanchev
conference: "Arxiv"
year: 2023
bibkey: braunschweiler2023evaluating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2309.11838'}
tags: ['Training Techniques', 'Model Architecture', 'GPT', 'Prompting', 'Pretraining Methods']
---
In this paper, we investigate the use of large language models (LLMs) like
ChatGPT for document-grounded response generation in the context of
information-seeking dialogues. For evaluation, we use the MultiDoc2Dial corpus
of task-oriented dialogues in four social service domains previously used in
the DialDoc 2022 Shared Task. Information-seeking dialogue turns are grounded
in multiple documents providing relevant information. We generate dialogue
completion responses by prompting a ChatGPT model, using two methods:
Chat-Completion and LlamaIndex. ChatCompletion uses knowledge from ChatGPT
model pretraining while LlamaIndex also extracts relevant information from
documents. Observing that document-grounded response generation via LLMs cannot
be adequately assessed by automatic evaluation metrics as they are
significantly more verbose, we perform a human evaluation where annotators rate
the output of the shared task winning system, the two Chat-GPT variants
outputs, and human responses. While both ChatGPT variants are more likely to
include information not present in the relevant segments, possibly including a
presence of hallucinations, they are rated higher than both the shared task
winning system and human responses.
