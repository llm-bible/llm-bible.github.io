---
layout: publication
title: Few-shot Question Answering By Pretraining Span Selection
authors: Ori Ram, Yuval Kirstain, Jonathan Berant, Amir Globerson, Omer Levy
conference: Arxiv
year: 2021
citations: 19
bibkey: ram2021few
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2101.00438'}]
tags: [Fine-Tuning, Few-Shot, Pre-Training]
---
In several question answering benchmarks, pretrained models have reached
human parity through fine-tuning on an order of 100,000 annotated questions and
answers. We explore the more realistic few-shot setting, where only a few
hundred training examples are available, and observe that standard models
perform poorly, highlighting the discrepancy between current pretraining
objectives and question answering. We propose a new pretraining scheme tailored
for question answering: recurring span selection. Given a passage with multiple
sets of recurring spans, we mask in each set all recurring spans but one, and
ask the model to select the correct span in the passage for each masked span.
Masked spans are replaced with a special token, viewed as a question
representation, that is later used during fine-tuning to select the answer
span. The resulting model obtains surprisingly good results on multiple
benchmarks (e.g., 72.7 F1 on SQuAD with only 128 training examples), while
maintaining competitive performance in the high-resource setting.