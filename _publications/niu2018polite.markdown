---
layout: publication
title: Polite Dialogue Generation Without Parallel Data
authors: Niu Tong, Bansal Mohit
conference: "Arxiv"
year: 2018
bibkey: niu2018polite
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1805.03162"}
tags: ['Agentic', 'Applications', 'Attention Mechanism', 'Merging', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Stylistic dialogue response generation with valuable applications in personality45;based conversational agents is a challenging task because the response needs to be fluent contextually45;relevant as well as paralinguistically accurate. Moreover parallel datasets for regular45;to45;stylistic pairs are usually unavailable. We present three weakly45;supervised models that can generate diverse polite (or rude) dialogue responses without parallel data. Our late fusion model (Fusion) merges the decoder of an encoder45;attention45;decoder dialogue model with a language model trained on stand45;alone polite utterances. Our label45;fine45;tuning (LFT) model prepends to each source sequence a politeness45;score scaled label (predicted by our state45;of45;the45;art politeness classifier) during training and at test time is able to generate polite neutral and rude responses by simply scaling the label embedding by the corresponding score. Our reinforcement learning model (Polite45;RL) encourages politeness generation by assigning rewards proportional to the politeness classifier score of the sampled response. We also present two retrieval45;based polite dialogue model baselines. Human evaluation validates that while the Fusion and the retrieval45;based models achieve politeness with poorer context45;relevance the LFT and Polite45;RL models can produce significantly more polite responses without sacrificing dialogue quality.
