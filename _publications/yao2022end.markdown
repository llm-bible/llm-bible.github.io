---
layout: publication
title: 'End-to-end Multimodal Fact-checking And Explanation Generation: A Challenging
  Dataset And Models'
authors: Barry Menglong Virginia Tech Yao, Aditya Virginia Tech Shah, Lichao Lehigh
  University Sun, Jin-hee Virginia Tech Cho, Lifu Virginia Tech Huang
conference: Proceedings of the 46th International ACM SIGIR Conference on Research
  and Development in Information Retrieval (SIGIR 23) July 23--27 2023 Taipei Taiwan
year: 2022
citations: 25
bibkey: yao2022end
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2205.12487'}, {name: Code,
    url: 'https://github.com/VT-NLP/Mocheg'}]
tags: [Multimodal Models, RAG, Interpretability and Explainability]
---
We propose end-to-end multimodal fact-checking and explanation generation,
where the input is a claim and a large collection of web sources, including
articles, images, videos, and tweets, and the goal is to assess the
truthfulness of the claim by retrieving relevant evidence and predicting a
truthfulness label (e.g., support, refute or not enough information), and to
generate a statement to summarize and explain the reasoning and ruling process.
To support this research, we construct Mocheg, a large-scale dataset consisting
of 15,601 claims where each claim is annotated with a truthfulness label and a
ruling statement, and 33,880 textual paragraphs and 12,112 images in total as
evidence. To establish baseline performances on Mocheg, we experiment with
several state-of-the-art neural architectures on the three pipelined subtasks:
multimodal evidence retrieval, claim verification, and explanation generation,
and demonstrate that the performance of the state-of-the-art end-to-end
multimodal fact-checking does not provide satisfactory outcomes. To the best of
our knowledge, we are the first to build the benchmark dataset and solutions
for end-to-end multimodal fact-checking and explanation generation. The
dataset, source code and model checkpoints are available at
https://github.com/VT-NLP/Mocheg.