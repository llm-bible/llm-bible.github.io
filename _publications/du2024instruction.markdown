---
layout: publication
title: 'Instruction-guided Scene Text Recognition'
authors: Yongkun Du, Zhineng Chen, Yuchen Su, Caiyan Jia, Yu-gang Jiang
conference: "Arxiv"
year: 2024
bibkey: du2024instruction
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.17851"}
  - {name: "Code", url: "https://github.com/Topdu/OpenOCR"}
tags: ['Training Techniques', 'Multimodal Models', 'Has Code', 'Merging']
---
Multi-modal models have shown appealing performance in visual recognition
tasks, as free-form text-guided training evokes the ability to understand
fine-grained visual content. However, current models cannot be trivially
applied to scene text recognition (STR) due to the compositional difference
between natural and text images. We propose a novel instruction-guided scene
text recognition (IGTR) paradigm that formulates STR as an instruction learning
problem and understands text images by predicting character attributes, e.g.,
character frequency, position, etc. IGTR first devises \\(\left \langle
condition,question,answer\right \rangle\\) instruction triplets, providing rich
and diverse descriptions of character attributes. To effectively learn these
attributes through question-answering, IGTR develops a lightweight instruction
encoder, a cross-modal feature fusion module and a multi-task answer head,
which guides nuanced text image understanding. Furthermore, IGTR realizes
different recognition pipelines simply by using different instructions,
enabling a character-understanding-based text reasoning paradigm that differs
from current methods considerably. Experiments on English and Chinese
benchmarks show that IGTR outperforms existing models by significant margins,
while maintaining a small model size and fast inference speed. Moreover, by
adjusting the sampling of instructions, IGTR offers an elegant way to tackle
the recognition of rarely appearing and morphologically similar characters,
which were previous challenges. Code: https://github.com/Topdu/OpenOCR.
