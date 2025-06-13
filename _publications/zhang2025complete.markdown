---
layout: publication
title: 'Complete Chess Games Enable LLM Become A Chess Master'
authors: Yinqi Zhang, Xintian Han, Haolong Li, Kedi Chen, Shaohui Lin
conference: "Arxiv"
year: 2025
bibkey: zhang2025complete
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.17186"}
tags: ['Fine-Tuning', 'Tools', 'Applications', 'Training Techniques', 'Pretraining Methods']
---
Large language models (LLM) have shown remarkable abilities in text
generation, question answering, language translation, reasoning and many other
tasks. It continues to advance rapidly and is becoming increasingly influential
in various fields, from technology and business to education and entertainment.
Despite LLM's success in multiple areas, its ability to play abstract games,
such as chess, is underexplored. Chess-playing requires the language models to
output legal and reasonable moves from textual inputs. Here, we propose the
Large language model ChessLLM to play full chess games. We transform the game
into a textual format with the best move represented in the Forsyth-Edwards
Notation. We show that by simply supervised fine-tuning, our model has achieved
a professional-level Elo rating of 1788 in matches against the standard
Elo-rated Stockfish when permitted to sample 10 times. We further show that
data quality is important. Long-round data supervision enjoys a 350 Elo rating
improvement over short-round data.
