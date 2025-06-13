---
layout: publication
title: 'SWITCH: Studying With Teacher For Knowledge Distillation Of Large Language Models'
authors: Jahyun Koo, Yerin Hwang, Yongil Kim, Taegwan Kang, Hyunkyung Bae, Kyomin Jung
conference: "Arxiv"
year: 2024
bibkey: koo2024studying
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.19503'}
tags: ['Efficiency and Optimization', 'Distillation', 'Training Techniques', 'Quantization', 'Reinforcement Learning', 'Ethics and Bias']
---
Despite the success of Large Language Models (LLMs), they still face
challenges related to high inference costs and memory requirements. To address
these issues, Knowledge Distillation (KD) has emerged as a popular method for
model compression, with student-generated outputs (SGOs) as training data being
particularly notable for reducing the mismatch between training and inference.
However, SGOs often produce noisy and biased sequences, which can lead to
misguidance from the teacher model, especially in long sequences. To mitigate
these challenges, we propose SWITCH (Studying WIth TeaCHer for Knowledge
Distillation), a novel approach that strategically incorporates the teacher
model during the student's sequence generation. SWITCH identifies discrepancies
between the token probabilities of the teacher and student models, allowing the
teacher to intervene selectively, particularly in long sequences that are more
prone to teacher misguidance. Extensive experimental results across three model
families and five instruction-following datasets show that SWITCH surpasses
traditional KD methods, particularly excelling in the generation of long
sequential data.
