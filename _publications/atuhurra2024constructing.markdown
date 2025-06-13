---
layout: publication
title: 'Constructing Multilingual Visual-text Datasets Revealing Visual Multilingual Ability Of Vision Language Models'
authors: Jesse Atuhurra, Iqra Ali, Tatsuya Hiraoka, Hidetaka Kamigaito, Tomoya Iwakura, Taro Watanabe
conference: "Arxiv"
year: 2024
bibkey: atuhurra2024constructing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.15359"}
tags: ['Prompting', 'Multimodal Models', 'Model Architecture', 'GPT']
---
Large language models (LLMs) have increased interest in vision language
models (VLMs), which process image-text pairs as input. Studies investigating
the visual understanding ability of VLMs have been proposed, but such studies
are still preliminary because existing datasets do not permit a comprehensive
evaluation of the fine-grained visual linguistic abilities of VLMs across
multiple languages. To further explore the strengths of VLMs, such as GPT-4V
\cite\{openai2023GPT4\}, we developed new datasets for the systematic and
qualitative analysis of VLMs. Our contribution is four-fold: 1) we introduced
nine vision-and-language (VL) tasks (including object recognition, image-text
matching, and more) and constructed multilingual visual-text datasets in four
languages: English, Japanese, Swahili, and Urdu through utilizing templates
containing \textit\{questions\} and prompting GPT4-V to generate the
\textit\{answers\} and the \textit\{rationales\}, 2) introduced a new VL task named
\textit\{unrelatedness\}, 3) introduced rationales to enable human understanding
of the VLM reasoning process, and 4) employed human evaluation to measure the
suitability of proposed datasets for VL tasks. We show that VLMs can be
fine-tuned on our datasets. Our work is the first to conduct such analyses in
Swahili and Urdu. Also, it introduces \textit\{rationales\} in VL analysis, which
played a vital role in the evaluation.
