---
layout: publication
title: "Learning Better Visual Dialog Agents With Pretrained Visual-linguistic Representation"
authors: Tu Tao, Ping Qing, Thattai Govind, Tur Gokhan, Natarajan Prem
conference: "Arxiv"
year: 2021
bibkey: tu2021learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2105.11541"}
tags: ['Agentic', 'BERT', 'Merging', 'Model Architecture', 'Reinforcement Learning', 'Tools']
---
GuessWhat! is a two-player visual dialog guessing game where player A asks a sequence of yes/no questions (Questioner) and makes a final guess (Guesser) about a target object in an image based on answers from player B (Oracle). Based on this dialog history between the Questioner and the Oracle a Guesser makes a final guess of the target object. Previous baseline Oracle model encodes no visual information in the model and it cannot fully understand complex questions about color shape relationships and so on. Most existing work for Guesser encode the dialog history as a whole and train the Guesser models from scratch on the GuessWhat! dataset. This is problematic since language encoder tend to forget long-term history and the GuessWhat! data is sparse in terms of learning visual grounding of objects. Previous work for Questioner introduces state tracking mechanism into the model but it is learned as a soft intermediates without any prior vision-linguistic insights. To bridge these gaps in this paper we propose Vilbert-based Oracle Guesser and Questioner which are all built on top of pretrained vision-linguistic model Vilbert. We introduce two-way background/target fusion mechanism into Vilbert-Oracle to account for both intra and inter-object questions. We propose a unified framework for Vilbert-Guesser and Vilbert-Questioner where state-estimator is introduced to best utilize Vilberts power on single-turn referring expression comprehension. Experimental results show that our proposed models outperform state-of-the-art models significantly by 737; 1037; 1237; for Oracle Guesser and End-to-End Questioner respectively.
