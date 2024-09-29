---
layout: publication
title: Making History Matter History45;advantage Sequence Training For Visual Dialog
authors: Yang Tianhao, Zha Zheng-jun, Zhang Hanwang
conference: "Arxiv"
year: 2019
bibkey: yang2019making
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1902.09326"}
tags: ['Agentic', 'Attention Mechanism', 'Ethics And Bias', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning', 'Training Techniques']
---
We study the multi45;round response generation in visual dialog where a response is generated according to a visually grounded conversational history. Given a triplet an image Qamp;A history and current question all the prevailing methods follow a codec (i.e. encoder45;decoder) fashion in a supervised learning paradigm a multimodal encoder encodes the triplet into a feature vector which is then fed into the decoder for the current answer generation supervised by the ground45;truth. However this conventional supervised learning does NOT take into account the impact of imperfect history violating the conversational nature of visual dialog and thus making the codec more inclined to learn history bias but not contextual reasoning. To this end inspired by the actor45;critic policy gradient in reinforcement learning we propose a novel training paradigm called History Advantage Sequence Training (HAST). Specifically we intentionally impose wrong answers in the history obtaining an adverse critic and see how the historic error impacts the codecs future behavior by History Advantage45;a quantity obtained by subtracting the adverse critic from the gold reward of ground45;truth history. Moreover to make the codec more sensitive to the history we propose a novel attention network called History45;Aware Co45;Attention Network (HACAN) which can be effectively trained by using HAST. Experimental results on three benchmarks VisDial v0.9amp;v1.0 and GuessWhat! show that the proposed HAST strategy consistently outperforms the state45;of45;the45;art supervised counterparts.
