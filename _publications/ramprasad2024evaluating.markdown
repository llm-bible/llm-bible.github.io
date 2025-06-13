---
layout: publication
title: 'Evaluating The Factuality Of Zero-shot Summarizers Across Varied Domains'
authors: Sanjana Ramprasad, Kundan Krishna, Zachary C Lipton, Byron C Wallace
conference: "Arxiv"
year: 2024
bibkey: ramprasad2024evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.03509"}
  - {name: "Code", url: "https://github.com/sanjanaramprasad/zero_shot_faceval_domains"}
tags: ['Pretraining Methods', 'Training Techniques', 'Applications', 'Has Code']
---
Recent work has shown that large language models (LLMs) are capable of
generating summaries zero-shot (i.e., without explicit supervision) that, under
human assessment, are often comparable or even preferred to manually composed
reference summaries. However, this prior work has focussed almost exclusively
on evaluating news article summarization. How do zero-shot summarizers perform
in other (potentially more specialized) domains? In this work we evaluate
zero-shot generated summaries across specialized domains including biomedical
articles, and legal bills (in addition to standard news benchmarks for
reference). We focus especially on the factuality of outputs. We acquire
annotations from domain experts to identify inconsistencies in summaries and
systematically categorize these errors. We analyze whether the prevalence of a
given domain in the pretraining corpus affects extractiveness and faithfulness
of generated summaries of articles in this domain. We release all collected
annotations to facilitate additional research toward measuring and realizing
factually accurate summarization, beyond news articles. The dataset can be
downloaded from https://github.com/sanjanaramprasad/zero_shot_faceval_domains
