---
layout: publication
title: 'Freeal: Towards Human-free Active Learning In The Era Of Large Language Models'
authors: Ruixuan Xiao, Yiwen Dong, Junbo Zhao, Runze Wu, Minmin Lin, Gang Chen, Haobo Wang
conference: "Arxiv"
year: 2023
bibkey: xiao2023towards
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2311.15614'}
  - {name: "Code", url: 'https://github.com/Justherozen/FreeAL'}
tags: ['Has Code', 'Training Techniques', 'Tools', 'Prompting', 'In-Context Learning']
---
Collecting high-quality labeled data for model training is notoriously
time-consuming and labor-intensive for various NLP tasks. While copious
solutions, such as active learning for small language models (SLMs) and
prevalent in-context learning in the era of large language models (LLMs), have
been proposed and alleviate the labeling burden to some extent, their
performances are still subject to human intervention. It is still underexplored
how to reduce the annotation cost in the LLMs era. To bridge this, we
revolutionize traditional active learning and propose an innovative
collaborative learning framework FreeAL to interactively distill and filter the
task-specific knowledge from LLMs. During collaborative training, an LLM serves
as an active annotator inculcating its coarse-grained knowledge, while a
downstream SLM is incurred as a student to filter out high-quality in-context
samples to feedback LLM for the subsequent label refinery. Extensive
experiments on eight benchmark datasets demonstrate that FreeAL largely
enhances the zero-shot performances for both SLM and LLM without any human
supervision. The code is available at https://github.com/Justherozen/FreeAL .
