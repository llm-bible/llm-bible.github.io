---
layout: publication
title: 'Visual Perception In Text Strings'
authors: Qi Jia, Xiang Yue, Shanshan Huang, Ziheng Qin, Yizhu Liu, Bill Yuchen Lin, Yang You
conference: "Arxiv"
year: 2024
bibkey: jia2024visual
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.01733'}
tags: ['RAG', 'Training Techniques', 'GPT', 'Model Architecture', 'Fine-Tuning', 'Merging', 'Reinforcement Learning', 'Pretraining Methods']
---
Understanding visual semantics embedded in consecutive characters is a
crucial capability for both large language models (LLMs) and multi-modal large
language models (MLLMs). This type of artifact possesses the unique
characteristic that identical information can be readily formulated in both
texts and images, making them a significant proxy for analyzing modern LLMs'
and MLLMs' capabilities in modality-agnostic vision understanding. In this
work, we select ASCII art as a representative artifact, where the lines and
brightness used to depict each concept are rendered by characters, and we frame
the problem as an ASCII art recognition task. We benchmark model performance on
this task by constructing an evaluation dataset with an elaborate
categorization tree and also collect a training set to elicit the models'
visual perception ability. Through a comprehensive analysis of dozens of
models, results reveal that although humans can achieve nearly 100% accuracy,
the state-of-the-art LLMs and MLLMs lag far behind. Models are capable of
recognizing concepts depicted in the ASCII arts given only text inputs
indicated by over 60% accuracy for some concepts, but most of them achieves
merely around 30% accuracy when averaged across all categories. When provided
with images as inputs, GPT-4o gets 82.68%, outperforming the strongest
open-source MLLM by 21.95%. Although models favor different kinds of ASCII art
depending on the modality provided, none of the MLLMs successfully benefit when
both modalities are supplied simultaneously. Moreover, supervised fine-tuning
helps improve models' accuracy especially when provided with the image
modality, but also highlights the need for better training techniques to
enhance the information fusion among modalities.
