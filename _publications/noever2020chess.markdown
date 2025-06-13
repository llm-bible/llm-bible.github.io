---
layout: publication
title: 'The Chess Transformer: Mastering Play Using Generative Language Models'
authors: David Noever, Matt Ciolino, Josh Kalin
conference: "Arxiv"
year: 2020
bibkey: noever2020chess
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2008.04057"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'GPT', 'Pretraining Methods', 'Transformer', 'Fine-Tuning']
---
This work demonstrates that natural language transformers can support more
generic strategic modeling, particularly for text-archived games. In addition
to learning natural language skills, the abstract transformer architecture can
generate meaningful moves on a chessboard. With further fine-tuning, the
transformer learns complex gameplay by training on 2.8 million chess games in
Portable Game Notation. After 30,000 training steps, OpenAI's Generative
Pre-trained Transformer (GPT-2) optimizes weights for 774 million parameters.
This fine-tuned Chess Transformer generates plausible strategies and displays
game formations identifiable as classic openings, such as English or the Slav
Exchange. Finally, in live play, the novel model demonstrates a
human-to-transformer interface that correctly filters illegal moves and
provides a novel method to challenge the transformer's chess strategies. We
anticipate future work will build on this transformer's promise, particularly
in other strategy games where features can capture the underlying complex rule
syntax from simple but expressive player annotations.
