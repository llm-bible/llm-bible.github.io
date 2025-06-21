---
layout: publication
title: Recursively Summarizing Books With Human Feedback
authors: Jeff Wu et al.
conference: Arxiv
year: 2021
citations: 63
bibkey: wu2021recursively
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2109.10862'}]
tags: [GPT, Reinforcement Learning, Fine-Tuning]
---
A major challenge for scaling machine learning is training models to perform
tasks that are very difficult or time-consuming for humans to evaluate. We
present progress on this problem on the task of abstractive summarization of
entire fiction novels. Our method combines learning from human feedback with
recursive task decomposition: we use models trained on smaller parts of the
task to assist humans in giving feedback on the broader task. We collect a
large volume of demonstrations and comparisons from human labelers, and
fine-tune GPT-3 using behavioral cloning and reward modeling to do
summarization recursively. At inference time, the model first summarizes small
sections of the book and then recursively summarizes these summaries to produce
a summary of the entire book. Our human labelers are able to supervise and
evaluate the models quickly, despite not having read the entire books
themselves. Our resulting model generates sensible summaries of entire books,
even matching the quality of human-written summaries in a few cases (\\(\sim5%\\)
of books). We achieve state-of-the-art results on the recent BookSum dataset
for book-length summarization. A zero-shot question-answering model using these
summaries achieves state-of-the-art results on the challenging NarrativeQA
benchmark for answering questions about books and movie scripts. We release
datasets of samples from our model.