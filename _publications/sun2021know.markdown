---
layout: publication
title: Know Deeper Knowledge-conversation Cyclic Utilization Mechanism For Open-domain Dialogue Generation
authors: Sun Yajing, Hu Yue, Xing Luxi, Xie Yuqiang, Wei Xiangpeng
conference: "Arxiv"
year: 2021
bibkey: sun2021know
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2107.07771"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'RAG']
---
End-to-End intelligent neural dialogue systems suffer from the problems of generating inconsistent and repetitive responses. Existing dialogue models pay attention to unilaterally incorporating personal knowledge into the dialog while ignoring the fact that incorporating the personality-related conversation information into personal knowledge taken as the bilateral information flow boosts the quality of the subsequent conversation. Besides it is indispensable to control personal knowledge utilization over the conversation level. In this paper we propose a conversation-adaption multi-view persona aware response generation model that aims at enhancing conversation consistency and alleviating the repetition from two folds. First we consider conversation consistency from multiple views. From the view of the persona profile we design a novel interaction module that not only iteratively incorporates personalized knowledge into each turn conversation but also captures the personality-related information from conversation to enhance personalized knowledge semantic representation. From the view of speaking style we introduce the speaking style vector and feed it into the decoder to keep the speaking style consistency. To avoid conversation repetition we devise a coverage mechanism to keep track of the activation of personal knowledge utilization. Experiments on both automatic and human evaluation verify the superiority of our model over previous models.
