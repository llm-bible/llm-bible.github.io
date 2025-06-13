---
layout: publication
title: 'LCFO: Long Context And Long Form Output Dataset And Benchmarking'
authors: Marta R. Costa-jussà, Pierre Andrews, Mariano Coria Meglioli, Joy Chen, Joe Chuang, David Dale, Christophe Ropers, Alexandre Mourachko, Eduardo Sánchez, Holger Schwenk, Tuan Tran, Arina Turkatenko, Carleigh Wood
conference: "Arxiv"
year: 2024
bibkey: costajussà2024long
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.08268'}
tags: ['RAG', 'Model Architecture', 'Tools', 'Applications', 'GPT']
---
This paper presents the Long Context and Form Output (LCFO) benchmark, a
novel evaluation framework for assessing gradual summarization and summary
expansion capabilities across diverse domains. LCFO consists of long input
documents (5k words average length), each of which comes with three summaries
of different lengths (20%, 10%, and 5% of the input text), as well as
approximately 15 questions and answers (QA) related to the input content.
Notably, LCFO also provides alignments between specific QA pairs and
corresponding summaries in 7 domains. The primary motivation behind providing
summaries of different lengths is to establish a controllable framework for
generating long texts from shorter inputs, i.e. summary expansion. To establish
an evaluation metric framework for summarization and summary expansion, we
provide human evaluation scores for human-generated outputs, as well as results
from various state-of-the-art large language models (LLMs). GPT-4o-mini
achieves best human scores among automatic systems in both summarization and
summary expansion tasks (~ +10% and +20%, respectively). It even surpasses
human output quality in the case of short summaries (~ +7%). Overall automatic
metrics achieve low correlations with human evaluation scores (~ 0.4) but
moderate correlation on specific evaluation aspects such as fluency and
attribution (~ 0.6). The LCFO benchmark offers a standardized platform for
evaluating summarization and summary expansion performance, as well as
corresponding automatic metrics, thereby providing an important evaluation
framework to advance generative AI.
