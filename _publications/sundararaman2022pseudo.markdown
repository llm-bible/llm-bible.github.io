---
layout: publication
title: 'Pseudo-ood Training For Robust Language Models'
authors: Dhanasekar Sundararaman, Nikhil Mehta, Lawrence Carin
conference: "Arxiv"
year: 2022
bibkey: sundararaman2022pseudo
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.09132"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Applications', 'Attention Mechanism']
---
While pre-trained large-scale deep models have garnered attention as an
important topic for many downstream natural language processing (NLP) tasks,
such models often make unreliable predictions on out-of-distribution (OOD)
inputs. As such, OOD detection is a key component of a reliable
machine-learning model for any industry-scale application. Common approaches
often assume access to additional OOD samples during the training stage,
however, outlier distribution is often unknown in advance. Instead, we propose
a post hoc framework called POORE - POsthoc pseudo-Ood REgularization, that
generates pseudo-OOD samples using in-distribution (IND) data. The model is
fine-tuned by introducing a new regularization loss that separates the
embeddings of IND and OOD data, which leads to significant gains on the OOD
prediction task during testing. We extensively evaluate our framework on three
real-world dialogue systems, achieving new state-of-the-art in OOD detection.
