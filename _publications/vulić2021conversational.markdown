---
layout: publication
title: Convfit Conversational Fine45;tuning Of Pretrained Language Models
authors: Vulić Ivan, Su Pei-hao, Coope Sam, Gerz Daniela, Budzianowski Paweł, Casanueva Iñigo, Mrkšić Nikola, Wen Tsung-hsien
conference: "Arxiv"
year: 2021
bibkey: vulić2021conversational
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2109.10126"}
tags: ['Model Architecture', 'Pretraining Methods', 'Security', 'Tools', 'Training Techniques', 'Transformer']
---
Transformer45;based language models (LMs) pretrained on large text collections are proven to store a wealth of semantic knowledge. However 1) they are not effective as sentence encoders when used off45;the45;shelf and 2) thus typically lag behind conversationally pretrained (e.g. via response selection) encoders on conversational tasks such as intent detection (ID). In this work we propose ConvFiT a simple and efficient two45;stage procedure which turns any pretrained LM into a universal conversational encoder (after Stage 1 ConvFiT45;ing) and task45;specialised sentence encoder (after Stage 2). We demonstrate that 1) full45;blown conversational pretraining is not required and that LMs can be quickly transformed into effective conversational encoders with much smaller amounts of unannotated data; 2) pretrained LMs can be fine45;tuned into task45;specialised sentence encoders optimised for the fine45;grained semantics of a particular task. Consequently such specialised sentence encoders allow for treating ID as a simple semantic similarity task based on interpretable nearest neighbours retrieval. We validate the robustness and versatility of the ConvFiT framework with such similarity45;based inference on the standard ID evaluation sets ConvFiT45;ed LMs achieve state45;of45;the45;art ID performance across the board with particular gains in the most challenging few45;shot setups.
