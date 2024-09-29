---
layout: publication
title: Iterative Vision45;and45;language Navigation
authors: Krantz Jacob, Banerjee Shurjo, Zhu Wang, Corso Jason, Anderson Peter, Lee Stefan, Thomason Jesse
conference: "Arxiv"
year: 2022
bibkey: krantz2022iterative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.03087"}
tags: ['Agentic', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
We present Iterative Vision45;and45;Language Navigation (IVLN) a paradigm for evaluating language45;guided agents navigating in a persistent environment over time. Existing Vision45;and45;Language Navigation (VLN) benchmarks erase the agents memory at the beginning of every episode testing the ability to perform cold45;start navigation with no prior information. However deployed robots occupy the same environment for long periods of time. The IVLN paradigm addresses this disparity by training and evaluating VLN agents that maintain memory across tours of scenes that consist of up to 100 ordered instruction45;following Room45;to45;Room (R2R) episodes each defined by an individual language instruction and a target path. We present discrete and continuous Iterative Room45;to45;Room (IR2R) benchmarks comprising about 400 tours each in 80 indoor scenes. We find that extending the implicit memory of high45;performing transformer VLN agents is not sufficient for IVLN but agents that build maps can benefit from environment persistence motivating a renewed focus on map45;building agents in VLN.
