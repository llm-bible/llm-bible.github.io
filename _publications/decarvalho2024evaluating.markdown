---
layout: publication
title: 'Show, Don''t Tell: Evaluating Large Language Models Beyond Textual Understanding With Childplay'
authors: Gonçalo Hora De Carvalho, Oscar Knap, Robert Pollice
conference: "Arxiv"
year: 2024
bibkey: decarvalho2024evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.11068"}
  - {name: "Code", url: "https://github.com/BlueVelvetSackOfGoldPotatoes/child-play}{{ChildPlay"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Reinforcement Learning']
---
We developed a benchmark set to assess the generalization of state-of-the-art
large language models on problems beyond linguistic tasks and evaluate it on a
systematic progression of GPT models (GPT-3.5, GPT-4, GPT-4o, GPT-4o-mini).
Using simple games like Tic-Tac-Toe, Connect Four, Battleship, and a Shape
Recognition Game, all encoded in ASCII, we test strategic capabilities and
spatial reasoning, core abilities any artificial intelligence would need to
master for solving problems in chemistry. To probe generalization, we introduce
two new games for spatial logic: LEGO Connect Language (LCL) and
Guess-the-SMILES (GtS), a operationally simple chemistry benchmark. Our results
show that GPT models provide meaningful responses for several tasks but,
generally, perform poorly. A systematic performance progression with increased
model capabilities (GPT-3.5, GPT-4, GPT-4o) is only observed for 4 out of the 7
benchmark tasks. All models consistently struggle with Battleship, LCL, and
GtS. This suggests that while GPT models can emulate conversational proficiency
and basic rule comprehension, they have limited generalization with respect to
strategy and spatial reasoning. Particularly poor performance is observed for
interpreting molecular graphs when encoded in ASCII. The results provided by
our open-source benchmark suite
(\href\{https://github.com/BlueVelvetSackOfGoldPotatoes/child-play\}\{\texttt\{ChildPlay\}
GitHub Repository\}) caution against claims of emergent intelligence in GPT
models, which appear more specialized than general.
