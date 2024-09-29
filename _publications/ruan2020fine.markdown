---
layout: publication
title: Fine45;tuning BERT For Schema45;guided Zero45;shot Dialogue State Tracking
authors: Ruan Yu-ping, Ling Zhen-hua, Gu Jia-chen, Liu Quan
conference: "Arxiv"
year: 2020
bibkey: ruan2020fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2002.00181"}
tags: ['Applications', 'BERT', 'Model Architecture', 'Tools']
---
We present our work on Track 4 in the Dialogue System Technology Challenges 8 (DSTC8). The DSTC845;Track 4 aims to perform dialogue state tracking (DST) under the zero45;shot settings in which the model needs to generalize on unseen service APIs given a schema definition of these target APIs. Serving as the core for many virtual assistants such as Siri Alexa and Google Assistant the DST keeps track of the users goal and what happened in the dialogue history mainly including intent prediction slot filling and user state tracking which tests models ability of natural language understanding. Recently the pretrained language models have achieved state45;of45;the45;art results and shown impressive generalization ability on various NLP tasks which provide a promising way to perform zero45;shot learning for language understanding. Based on this we propose a schema45;guided paradigm for zero45;shot dialogue state tracking (SGP45;DST) by fine45;tuning BERT one of the most popular pretrained language models. The SGP45;DST system contains four modules for intent prediction slot prediction slot transfer prediction and user state summarizing respectively. According to the official evaluation results our SGP45;DST (team12) ranked 3rd on the joint goal accuracy (primary evaluation metric for ranking submissions) and 1st on the requsted slots F1 among 25 participant teams.
