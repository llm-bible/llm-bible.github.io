---
layout: publication
title: 'Can Machines Read Coding Manuals Yet? -- A Benchmark For Building Better Language Models For Code Understanding'
authors: Ibrahim Abdelaziz, Julian Dolby, Jamie Mccusker, Kavitha Srinivas
conference: "Arxiv"
year: 2021
bibkey: abdelaziz2021can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2109.07452"}
tags: ['Training Techniques', 'BERT', 'Applications', 'Model Architecture']
---
Code understanding is an increasingly important application of Artificial
Intelligence. A fundamental aspect of understanding code is understanding text
about code, e.g., documentation and forum discussions. Pre-trained language
models (e.g., BERT) are a popular approach for various NLP tasks, and there are
now a variety of benchmarks, such as GLUE, to help improve the development of
such models for natural language understanding. However, little is known about
how well such models work on textual artifacts about code, and we are unaware
of any systematic set of downstream tasks for such an evaluation. In this
paper, we derive a set of benchmarks (BLANCA - Benchmarks for LANguage models
on Coding Artifacts) that assess code understanding based on tasks such as
predicting the best answer to a question in a forum post, finding related forum
posts, or predicting classes related in a hierarchy from class documentation.
We evaluate the performance of current state-of-the-art language models on
these tasks and show that there is a significant improvement on each task from
fine tuning. We also show that multi-task training over BLANCA tasks helps
build better language models for code understanding.
