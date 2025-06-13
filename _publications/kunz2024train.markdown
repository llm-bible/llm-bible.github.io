---
layout: publication
title: 'Train More Parameters But Mind Their Placement: Insights Into Language Adaptation With PEFT'
authors: Jenny Kunz
conference: "Arxiv"
year: 2024
bibkey: kunz2024train
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.12674'}
tags: ['Reinforcement Learning', 'Fine-Tuning', 'Training Techniques', 'Pretraining Methods']
---
Smaller LLMs still face significant challenges even in medium-resourced
languages, particularly when it comes to language-specific knowledge -- a
problem not easily resolved with machine-translated data. In this case study on
Icelandic, we aim to enhance the generation performance of an LLM by
specialising it using unstructured text corpora. A key focus is on preventing
interference with the models' capabilities of handling longer context during
this adaptation. Through ablation studies using various parameter-efficient
fine-tuning (PEFT) methods and setups, we find that increasing the number of
trainable parameters leads to better and more robust language adaptation. LoRAs
placed in the feed-forward layers and bottleneck adapters show promising
results with sufficient parameters, while prefix tuning and (IA)3 are not
suitable. Although improvements are consistent in 0-shot summarisation, some
adapted models struggle with longer context lengths, an issue that can be
mitigated by adapting only the final layers.
