---
layout: publication
title: Bundle MCR\: Towards Conversational Bundle Recommendation
authors: He Zhankui, Zhao Handong, Yu Tong, Kim Sungchul, Du Fan, Mcauley Julian
conference: "Arxiv"
year: 2022
bibkey: he2022bundle
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2207.12628"}
tags: ['Agentic', 'BERT', 'Fine Tuning', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques']
---
Bundle recommender systems recommend sets of items (e.g. pants shirt and shoes) to users but they often suffer from two issues significant interaction sparsity and a large output space. In this work we extend multi-round conversational recommendation (MCR) to alleviate these issues. MCR which uses a conversational paradigm to elicit user interests by asking user preferences on tags (e.g. categories or attributes) and handling user feedback across multiple rounds is an emerging recommendation setting to acquire user feedback and narrow down the output space but has not been explored in the context of bundle recommendation. In this work we propose a novel recommendation task named Bundle MCR. We first propose a new framework to formulate Bundle MCR as Markov Decision Processes (MDPs) with multiple agents for user modeling consultation and feedback handling in bundle contexts. Under this framework we propose a model architecture called Bundle Bert (Bunt) to (1) recommend items (2) post questions and (3) manage conversations based on bundle-aware conversation states. Moreover to train Bunt effectively we propose a two-stage training strategy. In an offline pre-training stage Bunt is trained using multiple cloze tasks to mimic bundle interactions in conversations. Then in an online fine-tuning stage Bunt agents are enhanced by user interactions. Our experiments on multiple offline datasets as well as the human evaluation show the value of extending MCR frameworks to bundle settings and the effectiveness of our Bunt design.
