---
layout: publication
title: Multimodal Transformer With Variable45;length Memory For Vision45;and45;language Navigation
authors: Lin Chuang, Jiang Yi, Cai Jianfei, Qu Lizhen, Haffari Gholamreza, Yuan Zehuan
conference: "Arxiv"
year: 2021
bibkey: lin2021multimodal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2111.05759"}
tags: ['Agentic', 'Attention Mechanism', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Transformer']
---
Vision45;and45;Language Navigation (VLN) is a task that an agent is required to follow a language instruction to navigate to the goal position which relies on the ongoing interactions with the environment during moving. Recent Transformer45;based VLN methods have made great progress benefiting from the direct connections between visual observations and the language instruction via the multimodal cross45;attention mechanism. However these methods usually represent temporal context as a fixed45;length vector by using an LSTM decoder or using manually designed hidden states to build a recurrent Transformer. Considering a single fixed45;length vector is often insufficient to capture long45;term temporal context in this paper we introduce Multimodal Transformer with Variable45;length Memory (MTVM) for visually45;grounded natural language navigation by modelling the temporal context explicitly. Specifically MTVM enables the agent to keep track of the navigation trajectory by directly storing previous activations in a memory bank. To further boost the performance we propose a memory45;aware consistency loss to help learn a better joint representation of temporal context with random masked instructions. We evaluate MTVM on popular R2R and CVDN datasets and our model improves Success Rate on R2R unseen validation and test set by 237; each and reduce Goal Process by 1.6m on CVDN test set.
