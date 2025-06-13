---
layout: publication
title: 'Ynote: A Novel Music Notation For Fine-tuning Llms In Music Generation'
authors: Shao-chien Lu, Chen-chen Yeh, Hui-lin Cho, Chun-chieh Hsu, Tsai-ling Hsu, Cheng-han Wu, Timothy K. Shih, Yu-cheng Lin
conference: "Arxiv"
year: 2025
bibkey: lu2025novel
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.10467"}
tags: ['Fine-Tuning', 'Tools', 'GPT', 'Applications', 'Model Architecture', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
The field of music generation using Large Language Models (LLMs) is evolving
rapidly, yet existing music notation systems, such as MIDI, ABC Notation, and
MusicXML, remain too complex for effective fine-tuning of LLMs. These formats
are difficult for both machines and humans to interpret due to their
variability and intricate structure. To address these challenges, we introduce
YNote, a simplified music notation system that uses only four characters to
represent a note and its pitch. YNote's fixed format ensures consistency,
making it easy to read and more suitable for fine-tuning LLMs. In our
experiments, we fine-tuned GPT-2 (124M) on a YNote-encoded dataset and achieved
BLEU and ROUGE scores of 0.883 and 0.766, respectively. With just two notes as
prompts, the model was able to generate coherent and stylistically relevant
music. We believe YNote offers a practical alternative to existing music
notations for machine learning applications and has the potential to
significantly enhance the quality of music generation using LLMs.
