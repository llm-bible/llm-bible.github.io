---
layout: publication
title: Guiding Large Language Models To Post-edit Machine Translation With Error Annotations
authors: Ki Dayeon, Carpuat Marine
conference: "NAACL"
year: 2024
bibkey: ki2024guiding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.07851"}
tags: ['Applications', 'Fine Tuning', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
Machine Translation (MT) remains one of the last NLP tasks where large language models (LLMs) have not yet replaced dedicated supervised systems. This work exploits the complementary strengths of LLMs and supervised MT by guiding LLMs to automatically post-edit MT with external feedback on its quality derived from Multidimensional Quality Metric (MQM) annotations. Working with LLaMA-2 models we consider prompting strategies varying the nature of feedback provided and then fine-tune the LLM to improve its ability to exploit the provided guidance. Through experiments on Chinese-English English-German and English-Russian MQM data we demonstrate that prompting LLMs to post-edit MT improves TER BLEU and COMET scores although the benefits of fine-grained feedback are not clear. Fine-tuning helps integrate fine-grained feedback more effectively and further improves translation quality based on both automatic and human evaluation.
