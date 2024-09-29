---
layout: publication
title: Modeling What45;to45;ask And How45;to45;ask For Answer45;unaware Conversational Question Generation
authors: Do Xuan Long, Zou Bowei, Joty Shafiq, Tran Anh Tai, Pan Liangming, Chen Nancy F., Aw Ai Ti
conference: "Arxiv"
year: 2023
bibkey: do2023modeling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.03088"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Reinforcement Learning', 'Tools']
---
Conversational Question Generation (CQG) is a critical task for machines to assist humans in fulfilling their information needs through conversations. The task is generally cast into two different settings answer45;aware and answer45;unaware. While the former facilitates the models by exposing the expected answer the latter is more realistic and receiving growing attentions recently. What45;to45;ask and how45;to45;ask are the two main challenges in the answer45;unaware setting. To address the first challenge existing methods mainly select sequential sentences in context as the rationales. We argue that the conversation generated using such naive heuristics may not be natural enough as in reality the interlocutors often talk about the relevant contents that are not necessarily sequential in context. Additionally previous methods decide the type of question to be generated (boolean/span45;based) implicitly. Modeling the question type explicitly is crucial as the answer which hints the models to generate a boolean or span45;based question is unavailable. To this end we present SG45;CQG a two45;stage CQG framework. For the what45;to45;ask stage a sentence is selected as the rationale from a semantic graph that we construct and extract the answer span from it. For the how45;to45;ask stage a classifier determines the target answer type of the question via two explicit control signals before generating and filtering. In addition we propose Conv45;Distinct a novel evaluation metric for CQG to evaluate the diversity of the generated conversation from a context. Compared with the existing answer45;unaware CQG models the proposed SG45;CQG achieves state45;of45;the45;art performance.
