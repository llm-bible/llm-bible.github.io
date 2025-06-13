---
layout: publication
title: 'Coprus: Consistency Preserving Utterance Synthesis Towards More Realistic Benchmark Dialogues'
authors: Sebastian Steindl, Ulrich Schäfer, Bernd Ludwig
conference: "Arxiv"
year: 2024
bibkey: steindl2024consistency
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.07515'}
tags: ['Reinforcement Learning', 'Applications', 'Training Techniques']
---
Large-scale Wizard-Of-Oz dialogue datasets have enabled the training of deep
learning-based dialogue systems. While they are successful as benchmark
datasets, they lack certain types of utterances, which would make them more
realistic. In this work, we investigate the creation of synthetic communication
errors in an automatic pipeline. Based on linguistic theory, we propose and
follow a simple error taxonomy. We focus on three types of miscommunications
that could happen in real-world dialogues but are underrepresented in the
benchmark dataset: misunderstandings, non-understandings and vaguely related
questions. Our two-step approach uses a state-of-the-art Large Language Model
(LLM) to first create the error and secondly the repairing utterance. We
perform Language Model-based evaluation to ensure the quality of the generated
utterances. We apply the method to the MultiWOZ dataset and evaluate it both
qualitatively and empirically as well as with human judges. Our results
indicate that current LLMs can aid in adding post-hoc miscommunications to
benchmark datasets as a form of data augmentation. We publish the resulting
dataset, in which nearly 1900 dialogues have been modified, as CoPrUS-MultiWOZ
to facilitate future work on dialogue systems.
