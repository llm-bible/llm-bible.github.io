---
layout: publication
title: 'Memory-augmented Recurrent Networks For Dialogue Coherence'
authors: Donahue David, Meng Yuanliang, Rumshisky Anna
conference: "Arxiv"
year: 2019
bibkey: donahue2019memory
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1910.10487"}
tags: ['Attention Mechanism', 'Model Architecture', 'RAG', 'Transformer']
---
Recent dialogue approaches operate by reading each word in a conversation
history, and aggregating accrued dialogue information into a single state. This
fixed-size vector is not expandable and must maintain a consistent format over
time. Other recent approaches exploit an attention mechanism to extract useful
information from past conversational utterances, but this introduces an
increased computational complexity. In this work, we explore the use of the
Neural Turing Machine (NTM) to provide a more permanent and flexible storage
mechanism for maintaining dialogue coherence. Specifically, we introduce two
separate dialogue architectures based on this NTM design. The first design
features a sequence-to-sequence architecture with two separate NTM modules, one
for each participant in the conversation. The second memory architecture
incorporates a single NTM module, which stores parallel context information for
both speakers. This second design also replaces the sequence-to-sequence
architecture with a neural language model, to allow for longer context of the
NTM and greater understanding of the dialogue history. We report perplexity
performance for both models, and compare them to existing baselines.
