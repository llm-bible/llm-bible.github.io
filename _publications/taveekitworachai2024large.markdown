---
layout: publication
title: 'Large Language Models Are Null-shot Learners'
authors: Taveekitworachai Pittawat, Abdullah Febri, Thawonmas Ruck
conference: "Arxiv"
year: 2024
bibkey: taveekitworachai2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.08273"}
tags: ['Applications', 'Prompting']
---
This paper presents null-shot prompting. Null-shot prompting exploits hallucination in large language models (LLMs) by instructing LLMs to utilize information from the Examples section that never exists within the provided context to perform a task. While reducing hallucination is crucial and non-negligible for daily and critical uses of LLMs, we propose that in the current landscape in which these LLMs still hallucinate, it is possible, in fact, to exploit hallucination to increase performance in performing tasks compared to standard zero-shot prompting. Experiments with eight LLMs show improvements in performance across the majority of eight datasets, including reading comprehension, arithmetic reasoning, and closed-book question answering. The observed inconsistency in increased relative performance across the LLMs also potentially indicates a different degree of inherent hallucination in each model. These differences show that it is possible to utilize null-shot prompting as a way to detect degrees of hallucination in LLMs using existing benchmarking datasets. We also perform ablation studies, including experimenting with a modified version of null-shot prompting that incorporates ideas from zero-shot chain-of-thought prompting, which shows different trends of results.
