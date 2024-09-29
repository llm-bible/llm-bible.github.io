---
layout: publication
title: Do Long45;range Language Models Actually Use Long45;range Context
authors: Sun Simeng, Krishna Kalpesh, Mattarella-micke Andrew, Iyyer Mohit
conference: "Arxiv"
year: 2021
bibkey: sun2021do
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2109.09115"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Transformer']
---
Language models are generally trained on short truncated input sequences which limits their ability to use discourse45;level information present in long45;range context to improve their predictions. Recent efforts to improve the efficiency of self45;attention have led to a proliferation of long45;range Transformer language models which can process much longer sequences than models of the past. However the ways in which such models take advantage of the long45;range context remain unclear. In this paper we perform a fine45;grained analysis of two long45;range Transformer language models (including the emph123;Routing Transformer125; which achieves state45;of45;the45;art perplexity on the PG45;19 long45;sequence LM benchmark dataset) that accept input sequences of up to 8K tokens. Our results reveal that providing long45;range context (i.e. beyond the previous 2K tokens) to these models only improves their predictions on a small set of tokens (e.g. those that can be copied from the distant context) and does not help at all for sentence45;level prediction tasks. Finally we discover that PG45;19 contains a variety of different document types and domains and that long45;range context helps most for literary novels (as opposed to textbooks or magazines).
