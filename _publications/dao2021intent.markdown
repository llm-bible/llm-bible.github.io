---
layout: publication
title: Intent Detection And Slot Filling For Vietnamese
authors: Mai Hoang Dao, Thinh Hung Truong, Dat Quoc Nguyen
conference: Arxiv
year: 2021
citations: 16
bibkey: dao2021intent
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.02021'}, {name: Code,
    url: 'https://github.com/VinAIResearch/JointIDSF'}]
tags: [BERT, Attention Mechanism, Model Architecture]
---
Intent detection and slot filling are important tasks in spoken and natural
language understanding. However, Vietnamese is a low-resource language in these
research topics. In this paper, we present the first public intent detection
and slot filling dataset for Vietnamese. In addition, we also propose a joint
model for intent detection and slot filling, that extends the recent
state-of-the-art JointBERT+CRF model with an intent-slot attention layer to
explicitly incorporate intent context information into slot filling via "soft"
intent label embedding. Experimental results on our Vietnamese dataset show
that our proposed model significantly outperforms JointBERT+CRF. We publicly
release our dataset and the implementation of our model at:
https://github.com/VinAIResearch/JointIDSF