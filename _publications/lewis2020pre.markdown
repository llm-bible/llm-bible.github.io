---
layout: publication
title: Pre-training Via Paraphrasing
authors: Mike Lewis et al.
conference: Arxiv
year: 2020
citations: 103
bibkey: lewis2020pre
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2006.15020'}]
tags: [Pre-Training, Fine-Tuning, Language Modeling, BERT]
---
We introduce MARGE, a pre-trained sequence-to-sequence model learned with an
unsupervised multi-lingual multi-document paraphrasing objective. MARGE
provides an alternative to the dominant masked language modeling paradigm,
where we self-supervise the reconstruction of target text by retrieving a set
of related texts (in many languages) and conditioning on them to maximize the
likelihood of generating the original. We show it is possible to jointly learn
to do retrieval and reconstruction, given only a random initialization. The
objective noisily captures aspects of paraphrase, translation, multi-document
summarization, and information retrieval, allowing for strong zero-shot
performance on several tasks. For example, with no additional task-specific
training we achieve BLEU scores of up to 35.8 for document translation. We
further show that fine-tuning gives strong performance on a range of
discriminative and generative tasks in many languages, making MARGE the most
generally applicable pre-training method to date.