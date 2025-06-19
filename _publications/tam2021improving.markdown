---
layout: publication
title: Improving And Simplifying Pattern Exploiting Training
authors: Derek Tam, Rakesh R Menon, Mohit Bansal, Shashank Srivastava, Colin Raffel
conference: Arxiv
year: 2021
citations: 32
bibkey: tam2021improving
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2103.11955'}, {name: Code,
    url: 'https://github.com/rrmenon10/ADAPET'}]
tags: [Fine-Tuning, Few-Shot]
---
Recently, pre-trained language models (LMs) have achieved strong performance
when fine-tuned on difficult benchmarks like SuperGLUE. However, performance
can suffer when there are very few labeled examples available for fine-tuning.
Pattern Exploiting Training (PET) is a recent approach that leverages patterns
for few-shot learning. However, PET uses task-specific unlabeled data. In this
paper, we focus on few-shot learning without any unlabeled data and introduce
ADAPET, which modifies PET's objective to provide denser supervision during
fine-tuning. As a result, ADAPET outperforms PET on SuperGLUE without any
task-specific unlabeled data. Our code can be found at
https://github.com/rrmenon10/ADAPET.