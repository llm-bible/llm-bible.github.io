---
layout: publication
title: 'Audio Dialogues: Dialogues Dataset For Audio And Music Understanding'
authors: Arushi Goel, Zhifeng Kong, Rafael Valle, Bryan Catanzaro
conference: "Arxiv"
year: 2024
bibkey: goel2024audio
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.07616'}
  - {name: "Code", url: 'https://audiodialogues.github.io/'}
tags: ['RAG', 'Has Code', 'Prompting', 'Applications']
---
Existing datasets for audio understanding primarily focus on single-turn
interactions (i.e. audio captioning, audio question answering) for describing
audio in natural language, thus limiting understanding audio via interactive
dialogue. To address this gap, we introduce Audio Dialogues: a multi-turn
dialogue dataset containing 163.8k samples for general audio sounds and music.
In addition to dialogues, Audio Dialogues also has question-answer pairs to
understand and compare multiple input audios together. Audio Dialogues
leverages a prompting-based approach and caption annotations from existing
datasets to generate multi-turn dialogues using a Large Language Model (LLM).
We evaluate existing audio-augmented large language models on our proposed
dataset to demonstrate the complexity and applicability of Audio Dialogues. Our
code for generating the dataset will be made publicly available. Detailed
prompts and generated dialogues can be found on the demo website
https://audiodialogues.github.io/.
