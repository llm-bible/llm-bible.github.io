---
layout: publication
title: "Dialogue-contextualized Re-ranking For Medical History-taking"
authors: Zhu Jian, Valmianski Ilya, Kannan Anitha
conference: "Arxiv"
year: 2023
bibkey: zhu2023dialogue
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.01974"}
tags: ['Applications', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
AI-driven medical history-taking is an important component in symptom checking automated patient intake triage and other AI virtual care applications. As history-taking is extremely varied machine learning models require a significant amount of data to train. To overcome this challenge existing systems are developed using indirect data or expert knowledge. This leads to a training-inference gap as models are trained on different kinds of data than what they observe at inference time. In this work we present a two-stage re-ranking approach that helps close the training-inference gap by re-ranking the first-stage question candidates using a dialogue-contextualized model. For this we propose a new model global re-ranker which cross-encodes the dialogue with all questions simultaneously and compare it with several existing neural baselines. We test both transformer and S4-based language model backbones. We find that relative to the expert system the best performance is achieved by our proposed global re-ranker with a transformer backbone resulting in a 3037; higher normalized discount cumulative gain (nDCG) and a 7737; higher mean average precision (mAP).
