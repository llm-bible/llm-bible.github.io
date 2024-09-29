---
layout: publication
title: LIMIT Less Is More For Instruction Tuning Across Evaluation Paradigms
authors: Jha Aditi, Havens Sam, Dohmann Jeremy, Trott Alex, Portes Jacob
conference: "Arxiv"
year: 2023
bibkey: jha2023less
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.13133"}
tags: ['Pretraining Methods', 'Tools']
---
Large Language Models are traditionally finetuned on large instruction datasets. However recent studies suggest that small high45;quality datasets can suffice for general purpose instruction following. This lack of consensus surrounding finetuning best practices is in part due to rapidly diverging approaches to LLM evaluation. In this study we ask whether a small amount of diverse finetuning samples can improve performance on both traditional perplexity45;based NLP benchmarks and on open45;ended model45;based evaluation. We finetune open45;source MPT45;7B and MPT45;30B models on instruction finetuning datasets of various sizes ranging from 1k to 60k samples. We find that subsets of 1k45;6k instruction finetuning samples are sufficient to achieve good performance on both (1) traditional NLP benchmarks and (2) model45;based evaluation. Finally we show that mixing textbook45;style and open45;ended QA finetuning datasets optimizes performance on both evaluation paradigms.
