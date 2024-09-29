---
layout: publication
title: LRTA A Transparent Neural45;symbolic Reasoning Framework With Modular Supervision For Visual Question Answering
authors: Liang Weixin, Niu Feiyang, Reganti Aishwarya, Thattai Govind, Tur Gokhan
conference: "Arxiv"
year: 2020
bibkey: liang2020transparent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2011.10731"}
tags: ['Applications', 'Tools', 'Training Techniques']
---
The predominant approach to visual question answering (VQA) relies on encoding the image and question with a black45;box neural encoder and decoding a single token as the answer like yes or no. Despite this approachs strong quantitative results it struggles to come up with intuitive human45;readable forms of justification for the prediction process. To address this insufficiency we reformulate VQA as a full answer generation task which requires the model to justify its predictions in natural language. We propose LRTA Look Read Think Answer a transparent neural45;symbolic reasoning framework for visual question answering that solves the problem step45;by45;step like humans and provides human45;readable form of justification at each step. Specifically LRTA learns to first convert an image into a scene graph and parse a question into multiple reasoning instructions. It then executes the reasoning instructions one at a time by traversing the scene graph using a recurrent neural45;symbolic execution module. Finally it generates a full answer to the given question with natural language justifications. Our experiments on GQA dataset show that LRTA outperforms the state45;of45;the45;art model by a large margin (43.137; v.s. 28.037;) on the full answer generation task. We also create a perturbed GQA test set by removing linguistic cues (attributes and relations) in the questions for analyzing whether a model is having a smart guess with superficial data correlations. We show that LRTA makes a step towards truly understanding the question while the state45;of45;the45;art model tends to learn superficial correlations from the training data.
