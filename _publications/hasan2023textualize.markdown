---
layout: publication
title: 'Textmi: Textualize Multimodal Information For Integrating Non-verbal Cues In Pre-trained Language Models'
authors: Md Kamrul Hasan, Md Saiful Islam, Sangwu Lee, Wasifur Rahman, Iftekhar Naim, Mohammed Ibrahim Khan, Ehsan Hoque
conference: "Arxiv"
year: 2023
bibkey: hasan2023textualize
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2303.15430'}
tags: ['Interpretability and Explainability', 'Training Techniques', 'BERT', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning']
---
Pre-trained large language models have recently achieved ground-breaking
performance in a wide variety of language understanding tasks. However, the
same model can not be applied to multimodal behavior understanding tasks (e.g.,
video sentiment/humor detection) unless non-verbal features (e.g., acoustic and
visual) can be integrated with language. Jointly modeling multiple modalities
significantly increases the model complexity, and makes the training process
data-hungry. While an enormous amount of text data is available via the web,
collecting large-scale multimodal behavioral video datasets is extremely
expensive, both in terms of time and money. In this paper, we investigate
whether large language models alone can successfully incorporate non-verbal
information when they are presented in textual form. We present a way to
convert the acoustic and visual information into corresponding textual
descriptions and concatenate them with the spoken text. We feed this augmented
input to a pre-trained BERT model and fine-tune it on three downstream
multimodal tasks: sentiment, humor, and sarcasm detection. Our approach,
TextMI, significantly reduces model complexity, adds interpretability to the
model's decision, and can be applied for a diverse set of tasks while achieving
superior (multimodal sarcasm detection) or near SOTA (multimodal sentiment
analysis and multimodal humor detection) performance. We propose TextMI as a
general, competitive baseline for multimodal behavioral analysis tasks,
particularly in a low-resource setting.
