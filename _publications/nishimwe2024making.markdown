---
layout: publication
title: 'Making Sentence Embeddings Robust To User-generated Content'
authors: Lydia Nishimwe, Benoît Sagot, Rachel Bawden
conference: "Arxiv"
year: 2024
bibkey: nishimwe2024making
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.17220"}
tags: ['Security', 'Training Techniques', 'Reinforcement Learning']
---
NLP models have been known to perform poorly on user-generated content (UGC),
mainly because it presents a lot of lexical variations and deviates from the
standard texts on which most of these models were trained. In this work, we
focus on the robustness of LASER, a sentence embedding model, to UGC data. We
evaluate this robustness by LASER's ability to represent non-standard sentences
and their standard counterparts close to each other in the embedding space.
Inspired by previous works extending LASER to other languages and modalities,
we propose RoLASER, a robust English encoder trained using a teacher-student
approach to reduce the distances between the representations of standard and
UGC sentences. We show that with training only on standard and synthetic
UGC-like data, RoLASER significantly improves LASER's robustness to both
natural and artificial UGC data by achieving up to 2x and 11x better scores. We
also perform a fine-grained analysis on artificial UGC data and find that our
model greatly outperforms LASER on its most challenging UGC phenomena such as
keyboard typos and social media abbreviations. Evaluation on downstream tasks
shows that RoLASER performs comparably to or better than LASER on standard
data, while consistently outperforming it on UGC data.
