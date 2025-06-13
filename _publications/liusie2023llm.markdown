---
layout: publication
title: 'LLM Comparative Assessment: Zero-shot NLG Evaluation Through Pairwise Comparisons Using Large Language Models'
authors: Adian Liusie, Potsawee Manakul, Mark J. F. Gales
conference: "Arxiv"
year: 2023
bibkey: liusie2023llm
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2307.07889'}
tags: ['Ethics and Bias', 'Prompting']
---
Current developments in large language models (LLMs) have enabled impressive
zero-shot capabilities across various natural language tasks. An interesting
application of these systems is in the automated assessment of natural language
generation (NLG), a highly challenging area with great practical benefit. In
this paper, we explore two options for exploiting the emergent abilities of
LLMs for zero-shot NLG assessment: absolute score prediction, and comparative
assessment which uses relative comparisons between pairs of candidates. Though
comparative assessment has not been extensively studied in NLG assessment, we
note that humans often find it more intuitive to compare two options rather
than scoring each one independently. This work examines comparative assessment
from multiple perspectives: performance compared to absolute grading;
positional biases in the prompt; and efficient ranking in terms of the number
of comparisons. We illustrate that LLM comparative assessment is a simple,
general and effective approach for NLG assessment. For moderate-sized
open-source LLMs, such as FlanT5 and Llama2-chat, comparative assessment is
superior to prompt scoring, and in many cases can achieve performance
competitive with state-of-the-art methods. Additionally, we demonstrate that
LLMs often exhibit strong positional biases when making pairwise comparisons,
and we propose debiasing methods that can further improve performance.
