---
layout: publication
title: 'Automatikz: Text-guided Synthesis Of Scientific Vector Graphics With Tikz'
authors: Jonas Belouadi, Anne Lauscher, Steffen Eger
conference: "The Twelfth International Conference on Learning Representations 2024"
year: 2023
bibkey: belouadi2023text
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2310.00367'}
tags: ['Attention Mechanism', 'GPT', 'Tools', 'Model Architecture', 'Multimodal Models']
---
Generating bitmap graphics from text has gained considerable attention, yet
for scientific figures, vector graphics are often preferred. Given that vector
graphics are typically encoded using low-level graphics primitives, generating
them directly is difficult. To address this, we propose the use of TikZ, a
well-known abstract graphics language that can be compiled to vector graphics,
as an intermediate representation of scientific figures. TikZ offers
human-oriented, high-level commands, thereby facilitating conditional language
modeling with any large language model. To this end, we introduce DaTikZ, the
first large-scale TikZ dataset consisting of 120k TikZ drawings aligned with
captions. We fine-tune LLaMA on DaTikZ, as well as our new model CLiMA, which
augments LLaMA with multimodal CLIP embeddings. In both human and automatic
evaluation, CLiMA and LLaMA outperform commercial GPT-4 and Claude 2 in terms
of similarity to human-created figures, with CLiMA additionally improving
text-image alignment. Our detailed analysis shows that all models generalize
well and are not susceptible to memorization. GPT-4 and Claude 2, however, tend
to generate more simplistic figures compared to both humans and our models. We
make our framework, AutomaTikZ, along with model weights and datasets, publicly
available.
