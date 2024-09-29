---
layout: publication
title: Atomic Self45;consistency For Better Long Form Generations
authors: Thirukovalluru Raghuveer, Huang Yukun, Dhingra Bhuwan
conference: "Arxiv"
year: 2024
bibkey: thirukovalluru2024atomic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.13131"}
tags: ['Applications', 'GPT', 'Merging', 'Model Architecture']
---
Recent work has aimed to improve LLM generations by filtering out hallucinations thereby improving the precision of the information in responses. Correctness of a long45;form response however also depends on the recall of multiple pieces of information relevant to the question. In this paper we introduce Atomic Self45;Consistency (ASC) a technique for improving the recall of relevant information in an LLM response. ASC follows recent work Universal Self45;Consistency (USC) in using multiple stochastic samples from an LLM to improve the long45;form response. Unlike USC which only focuses on selecting the best single generation ASC picks authentic subparts from the samples and merges them into a superior composite answer. Through extensive experiments and ablations we show that merging relevant subparts of multiple samples performs significantly better than picking a single sample. ASC demonstrates significant gains over USC on multiple factoids and open45;ended QA datasets 45; ASQA QAMPARI QUEST ELI5 with ChatGPT and Llama2. Our analysis also reveals untapped potential for enhancing long45;form generations using approach of merging multiple samples.
