---
layout: publication
title: Guiding Large Language Models To Post45;edit Machine Translation With Error Annotations
authors: Ki Dayeon, Carpuat Marine
conference: "NAACL"
year: 2024
bibkey: ki2024guiding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.07851"}
tags: ['Applications', 'Prompting']
---
Machine Translation (MT) remains one of the last NLP tasks where large language models (LLMs) have not yet replaced dedicated supervised systems. This work exploits the complementary strengths of LLMs and supervised MT by guiding LLMs to automatically post45;edit MT with external feedback on its quality derived from Multidimensional Quality Metric (MQM) annotations. Working with LLaMA45;2 models we consider prompting strategies varying the nature of feedback provided and then fine45;tune the LLM to improve its ability to exploit the provided guidance. Through experiments on Chinese45;English English45;German and English45;Russian MQM data we demonstrate that prompting LLMs to post45;edit MT improves TER BLEU and COMET scores although the benefits of fine45;grained feedback are not clear. Fine45;tuning helps integrate fine45;grained feedback more effectively and further improves translation quality based on both automatic and human evaluation.
