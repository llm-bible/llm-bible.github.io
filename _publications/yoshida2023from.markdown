---
layout: publication
title: 'From Text To Motion: Grounding GPT-4 In A Humanoid Robot "alter3"'
authors: Takahide Yoshida, Atsushi Masumori, Takashi Ikegami
conference: "Arxiv"
year: 2023
bibkey: yoshida2023from
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.06571"}
  - {name: "Code", url: "https://tnoinkwms.github.io/ALTER-LLM/"}
tags: ['Fine-Tuning', 'GPT', 'Model Architecture', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
We report the development of Alter3, a humanoid robot capable of generating
spontaneous motion using a Large Language Model (LLM), specifically GPT-4. This
achievement was realized by integrating GPT-4 into our proprietary android,
Alter3, thereby effectively grounding the LLM with Alter's bodily movement.
Typically, low-level robot control is hardware-dependent and falls outside the
scope of LLM corpora, presenting challenges for direct LLM-based robot control.
However, in the case of humanoid robots like Alter3, direct control is feasible
by mapping the linguistic expressions of human actions onto the robot's body
through program code. Remarkably, this approach enables Alter3 to adopt various
poses, such as a 'selfie' stance or 'pretending to be a ghost,' and generate
sequences of actions over time without explicit programming for each body part.
This demonstrates the robot's zero-shot learning capabilities. Additionally,
verbal feedback can adjust poses, obviating the need for fine-tuning. A video
of Alter3's generated motions is available at
https://tnoinkwms.github.io/ALTER-LLM/
