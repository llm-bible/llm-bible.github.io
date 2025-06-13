---
layout: publication
title: 'Voxtlm: Unified Decoder-only Models For Consolidating Speech Recognition/synthesis And Speech/text Continuation Tasks'
authors: Soumi Maiti, Yifan Peng, Shukjae Choi, Jee-weon Jung, Xuankai Chang, Shinji Watanabe
conference: "Arxiv"
year: 2023
bibkey: maiti2023unified
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.07937"}
tags: ['Language Modeling', 'Training Techniques', 'Applications', 'INTERSPEECH']
---
We propose a decoder-only language model, VoxtLM, that can perform four
tasks: speech recognition, speech synthesis, text generation, and speech
continuation. VoxtLM integrates text vocabulary with discrete speech tokens
from self-supervised speech features and uses special tokens to enable
multitask learning. Compared to a single-task model, VoxtLM exhibits a
significant improvement in speech synthesis, with improvements in both speech
intelligibility from 28.9 to 5.6 and objective quality from 2.68 to 3.90.
VoxtLM also improves speech generation and speech recognition performance over
the single-task counterpart. Further, VoxtLM is trained with publicly available
data and training recipes and model checkpoints are open-sourced to make fully
reproducible work.
