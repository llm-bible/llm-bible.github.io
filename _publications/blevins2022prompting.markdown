---
layout: publication
title: Prompting Language Models for Linguistic Structure
authors: Blevins Terra, Gonen Hila, Zettlemoyer Luke
conference: "Arxiv"
year: 2022
bibkey: blevins2022prompting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2211.07830"}
tags: ['Few Shot', 'GPT', 'In Context Learning', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
Although pretrained language models (PLMs) can be prompted to perform a wide range of language tasks it remains an open question how much this ability comes from generalizable linguistic understanding versus surface-level lexical patterns. To test this we present a structured prompting approach for linguistic structured prediction tasks allowing us to perform zero- and few-shot sequence tagging with autoregressive PLMs. We evaluate this approach on part-of-speech tagging named entity recognition and sentence chunking demonstrating strong few-shot performance in all cases. We also find that while PLMs contain significant prior knowledge of task labels due to task leakage into the pretraining corpus structured prompting can also retrieve linguistic structure with arbitrary labels. These findings indicate that the in-context learning ability and linguistic knowledge of PLMs generalizes beyond memorization of their training data.
