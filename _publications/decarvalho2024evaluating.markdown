---
layout: publication
title: Show Dont Tell Evaluating Large Language Models Beyond Textual Understanding With Childplay
authors: De Carvalho Gonçalo Hora, Knap Oscar, Pollice Robert
conference: "Arxiv"
year: 2024
bibkey: decarvalho2024evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.11068"}
  - {name: "Code", url: "https://github.com/child&#45;play&#45;neurips/child&#45;play)"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
We explore the hypothesis that LLMs such as GPT45;3.5 and GPT45;4 possess broader cognitive functions particularly in non45;linguistic domains. Our approach extends beyond standard linguistic benchmarks by incorporating games like Tic45;Tac45;Toe Connect Four and Battleship encoded via ASCII to assess strategic thinking and decision45;making. To evaluate the models ability to generalize beyond their training data we introduce two additional games. The first game LEGO Connect Language (LCL) tests the models capacity to understand spatial logic and follow assembly instructions. The second game the game of shapes challenges the models to identify shapes represented by 1s within a matrix of zeros further testing their spatial reasoning skills. This show dont tell strategy uses games instead of simply querying the models. Our results show that despite their proficiency on standard benchmarks GPT45;3.5 and GPT45;4s abilities to play and reason about fully observable games without pre45;training is mediocre. Both models fail to anticipate losing moves in Tic45;Tac45;Toe and Connect Four and they are unable to play Battleship correctly. While GPT45;4 shows some success in the game of shapes both models fail at the assembly tasks presented in the LCL game. These results suggest that while GPT models can emulate conversational proficiency and basic rule comprehension their performance in strategic gameplay and spatial reasoning tasks is very limited. Importantly this reveals a blind spot in current LLM benchmarks that we highlight with our gameplay benchmark suite ChildPlay (https://github.com/child&#45;play&#45;neurips/child&#45;play). Our findings provide a cautionary tale about claims of emergent intelligence and reasoning capabilities of LLMs that are roughly the size of GPT45;3.5 and GPT45;4.
