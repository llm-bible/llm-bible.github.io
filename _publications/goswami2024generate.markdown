---
layout: publication
title: 'Grape: A Generate-plan-edit Framework For Compositional T2I Synthesis'
authors: Ashish Goswami, Satyam Kumar Modi, Santhosh Rishi Deshineni, Harman Singh, Prathosh A. P, Parag Singla
conference: "Arxiv"
year: 2024
bibkey: goswami2024generate
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.06089'}
tags: ['Training Techniques', 'Prompting', 'Tools', 'Merging']
---
Text-to-image (T2I) generation has seen significant progress with diffusion
models, enabling generation of photo-realistic images from text prompts.
Despite this progress, existing methods still face challenges in following
complex text prompts, especially those requiring compositional and multi-step
reasoning. Given such complex instructions, SOTA models often make mistakes in
faithfully modeling object attributes, and relationships among them. In this
work, we present an alternate paradigm for T2I synthesis, decomposing the task
of complex multi-step generation into three steps, (a) Generate: we first
generate an image using existing diffusion models (b) Plan: we make use of
Multi-Modal LLMs (MLLMs) to identify the mistakes in the generated image
expressed in terms of individual objects and their properties, and produce a
sequence of corrective steps required in the form of an edit-plan. (c) Edit: we
make use of an existing text-guided image editing models to sequentially
execute our edit-plan over the generated image to get the desired image which
is faithful to the original instruction. Our approach derives its strength from
the fact that it is modular in nature, is training free, and can be applied
over any combination of image generation and editing models. As an added
contribution, we also develop a model capable of compositional editing, which
further helps improve the overall accuracy of our proposed approach. Our method
flexibly trades inference time compute with performance on compositional text
prompts. We perform extensive experimental evaluation across 3 benchmarks and
10 T2I models including DALLE-3 and the latest -- SD-3.5-Large. Our approach
not only improves the performance of the SOTA models, by upto 3 points, it also
reduces the performance gap between weaker and stronger models.
\\(\href\{https://dair-iitd.github.io/GraPE/\}\{https://dair-iitd.github.io/GraPE/\}\\)
