---
layout: publication
title: 'Polite Dialogue Generation Without Parallel Data'
authors: Niu Tong, Bansal Mohit
conference: "Arxiv"
year: 2018
bibkey: niu2018polite
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1805.03162"}
tags: ['Agentic', 'Applications', 'Attention Mechanism', 'Fine Tuning', 'Merging', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Stylistic dialogue response generation with valuable applications in personality-based conversational agents is a challenging task because the response needs to be fluent contextually-relevant as well as paralinguistically accurate. Moreover parallel datasets for regular-to-stylistic pairs are usually unavailable. We present three weakly-supervised models that can generate diverse polite (or rude) dialogue responses without parallel data. Our late fusion model (Fusion) merges the decoder of an encoder-attention-decoder dialogue model with a language model trained on stand-alone polite utterances. Our label-fine-tuning (LFT) model prepends to each source sequence a politeness-score scaled label (predicted by our state-of-the-art politeness classifier) during training and at test time is able to generate polite neutral and rude responses by simply scaling the label embedding by the corresponding score. Our reinforcement learning model (Polite-RL) encourages politeness generation by assigning rewards proportional to the politeness classifier score of the sampled response. We also present two retrieval-based polite dialogue model baselines. Human evaluation validates that while the Fusion and the retrieval-based models achieve politeness with poorer context-relevance the LFT and Polite-RL models can produce significantly more polite responses without sacrificing dialogue quality.
