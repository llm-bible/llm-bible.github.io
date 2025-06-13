---
layout: publication
title: 'Beyond Imitation: Leveraging Fine-grained Quality Signals For Alignment'
authors: Geyang Guo, Ranchi Zhao, Tianyi Tang, Wayne Xin Zhao, Ji-rong Wen
conference: "Arxiv"
year: 2023
bibkey: guo2023beyond
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.04072"}
tags: ['Fine-Tuning', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Alignment with human preference is a desired property of large language
models (LLMs). Currently, the main alignment approach is based on reinforcement
learning from human feedback (RLHF). Despite the effectiveness of RLHF, it is
intricate to implement and train, thus recent studies explore how to develop
alternative alignment approaches based on supervised fine-tuning (SFT). A major
limitation of SFT is that it essentially does imitation learning, which cannot
fully understand what are the expected behaviors. To address this issue, we
propose an improved alignment approach named FIGA. Different from prior
methods, we incorporate fine-grained (i.e., token or phrase level) quality
signals that are derived by contrasting good and bad responses. Our approach
has made two major contributions. Firstly, we curate a refined alignment
dataset that pairs initial responses and the corresponding revised ones.
Secondly, we devise a new loss function can leverage fine-grained quality
signals to instruct the learning of LLMs for alignment. Extensive experiments
have demonstrated the effectiveness of our approaches by comparing a number of
competitive baselines.
