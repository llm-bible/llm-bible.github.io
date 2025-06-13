---
layout: publication
title: 'Cerbero-7b: A Leap Forward In Language-specific Llms Through Enhanced Chat Corpus Generation And Evaluation'
authors: Federico A. Galatolo, Mario G. C. A. Cimino
conference: "Arxiv"
year: 2023
bibkey: galatolo2023cerbero
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.15698"}
tags: ['Transformer', 'GPT', 'Model Architecture', 'Masked Language Model', 'Pretraining Methods', 'BERT']
---
This study introduces a novel approach for generating high-quality,
language-specific chat corpora using a self-chat mechanism. We combine a
generator LLM for creating new samples and an embedder LLM to ensure diversity.
A new Masked Language Modelling (MLM) model-based quality assessment metric is
proposed for evaluating and filtering the corpora. Utilizing the llama2-70b as
the generator and a multilingual sentence transformer as embedder, we generate
an Italian chat corpus and refine the Fauno corpus, which is based on
translated English ChatGPT self-chat data. The refinement uses structural
assertions and Natural Language Processing techniques. Both corpora undergo a
comprehensive quality evaluation using the proposed MLM model-based quality
metric. The Italian LLM fine-tuned with these corpora demonstrates
significantly enhanced language comprehension and question-answering skills.
The resultant model, cerbero-7b, establishes a new state-of-the-art for Italian
LLMs. This approach marks a substantial advancement in the development of
language-specific LLMs, with a special emphasis on augmenting corpora for
underrepresented languages like Italian.
