---
layout: publication
title: 'Panza: Design And Analysis Of A Fully-local Personalized Text Writing Assistant'
authors: Armand Nicolicioiu, Eugenia Iofinova, Andrej Jovanovic, Eldar Kurtic, Mahdi Nikdan, Andrei Panferov, Ilia Markov, Nir Shavit, Dan Alistarh
conference: "Arxiv"
year: 2024
bibkey: nicolicioiu2024design
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.10994'}
  - {name: "Code", url: 'https://github.com/IST-DASLab/PanzaMail'}
tags: ['Has Code', 'RAG', 'Security', 'Training Techniques', 'Fine-Tuning', 'Pretraining Methods']
---
The availability of powerful open-source large language models (LLMs) opens
exciting use-cases, such as using personal data to fine-tune these models to
imitate a user's unique writing style. Two key requirements for such assistants
are personalization - in the sense that the assistant should recognizably
reflect the user's own writing style - and privacy - users may justifiably be
wary of uploading extremely personal data, such as their email archive, to a
third-party service. In this paper, we present a new design and evaluation for
such an automated assistant, for the specific use case of email generation,
which we call Panza. Panza's personalization features are based on a
combination of fine-tuning using a variant of the Reverse Instructions
technique together with Retrieval-Augmented Generation (RAG). We demonstrate
that this combination allows us to fine-tune an LLM to reflect a user's writing
style using limited data, while executing on extremely limited resources, e.g.
on a free Google Colab instance. Our key methodological contribution is the
first detailed study of evaluation metrics for this personalized writing task,
and of how different choices of system components--the use of RAG and of
different fine-tuning approaches-impact the system's performance. Additionally,
we demonstrate that very little data - under 100 email samples - are sufficient
to create models that convincingly imitate humans. This finding showcases a
previously-unknown attack vector in language models - that access to a small
number of writing samples can allow a bad actor to cheaply create generative
models that imitate a target's writing style. We are releasing the full Panza
code as well as three new email datasets licensed for research use at
https://github.com/IST-DASLab/PanzaMail.
