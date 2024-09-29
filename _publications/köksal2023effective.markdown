---
layout: publication
title: Longform&#58; Effective Instruction Tuning With Reverse Instructions
authors: Köksal Abdullatif, Schick Timo, Korhonen Anna, Schütze Hinrich
conference: "Arxiv"
year: 2023
bibkey: köksal2023effective
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.08460"}
  - {name: "Code", url: "https://github.com/akoksal/LongForm"}
tags: ['Applications', 'Fine Tuning', 'Has Code', 'Language Modeling']
---
Instruction tuning enables language models to more effectively generalize and better follow user intent. However obtaining instruction data is costly and challenging. Prior work employs methods such as expensive human annotation crowd-sourced datasets with alignment issues and generating noisy examples via LLMs. We introduce the LongForm-C dataset which is created by reverse instructions. We generate instructions via LLMs for human-written corpus examples using reverse instructions. First we select a diverse set of human-written documents from corpora such as C4 and Wikipedia; then we generate instructions for these documents via LLMs. This approach provides a cheaper and cleaner instruction-tuning dataset with natural output and one suitable for long text generation. Our models outperform 10x larger language models without instruction tuning on tasks such as story/recipe generation and long-form question answering. Moreover LongForm models outperform prior instruction-tuned models such as FLAN-T5 and Alpaca by a large margin and improve language understanding capabilities further. Finally our models can effectively follow and answer multilingual instructions; we demonstrate this for news generation. We publicly release our data and models https://github.com/akoksal/LongForm."
