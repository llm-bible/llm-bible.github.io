---
layout: publication
title: 'Privacy Ripple Effects From Adding Or Removing Personal Information In Language Model Training'
authors: Jaydeep Borkar, Matthew Jagielski, Katherine Lee, Niloofar Mireshghallah, David A. Smith, Christopher A. Choquette-choo
conference: "Arxiv"
year: 2025
bibkey: borkar2025privacy
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.15680'}
tags: ['Reinforcement Learning', 'Fine-Tuning', 'Training Techniques', 'Pretraining Methods']
---
Due to the sensitive nature of personally identifiable information (PII), its
owners may have the authority to control its inclusion or request its removal
from large-language model (LLM) training. Beyond this, PII may be added or
removed from training datasets due to evolving dataset curation techniques,
because they were newly scraped for retraining, or because they were included
in a new downstream fine-tuning stage. We find that the amount and ease of PII
memorization is a dynamic property of a model that evolves throughout training
pipelines and depends on commonly altered design choices. We characterize three
such novel phenomena: (1) similar-appearing PII seen later in training can
elicit memorization of earlier-seen sequences in what we call assisted
memorization, and this is a significant factor (in our settings, up to 1/3);
(2) adding PII can increase memorization of other PII significantly (in our
settings, as much as \\(\approx\!7.5\times\\)); and (3) removing PII can lead to
other PII being memorized. Model creators should consider these first- and
second-order privacy risks when training models to avoid the risk of new PII
regurgitation.
