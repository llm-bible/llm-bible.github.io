---
layout: publication
title: 'Train & Constrain: Phonologically Informed Tongue-twister Generation From Topics And Paraphrases'
authors: Tyler Loakman, Chen Tang, Chenghua Lin
conference: "Arxiv"
year: 2024
bibkey: loakman2024train
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2403.13901'}
tags: ['GPT', 'Training Techniques', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
Previous work in phonologically and phonetically grounded language generation
has mainly focused on domains such as puns and poetry. In this article, we
present new work on the generation of English tongue twisters - a form of
language that is required to be conditioned on a phoneme level to maximize
sound overlap, while maintaining semantic consistency with an input topic or
phrase and still being grammatically correct. We present TwisterLister, a
pipeline for generating phonologically informed tongue twisters from large
language models (LLMs) that we use to generate TwistList 2.0, the largest
annotated dataset of tongue twisters to date, consisting of 17K+ examples from
a combination of human and LLM authors. Our generation pipeline involves the
use of a phonologically constrained vocabulary alongside LLM prompting to
generate novel, non-derivative tongue twister examples. We additionally present
the results of automatic and human evaluation of smaller models trained on our
generated dataset to demonstrate the extent to which phonologically motivated
language types can be generated without explicit injection of phonological
knowledge. Additionally, we introduce a phoneme-aware constrained decoding
module (PACD) that can be integrated into an autoregressive language model and
demonstrate that this method generates good quality tongue twisters both with
and without fine-tuning the underlying language model. We also design and
implement a range of automatic metrics for the task of tongue twister
generation that is phonologically motivated and captures the unique essence of
tongue twisters, primarily based on phonemic edit distance (PED)
