---
layout: publication
title: Learning Video Representations From Large Language Models
authors: Zhao Yue, Misra Ishan, Krähenbühl Philipp, Girdhar Rohit
conference: "Arxiv"
year: 2022
bibkey: zhao2022learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.04501"}
tags: ['Pretraining Methods', 'RAG', 'Training Techniques']
---
We introduce LaViLa a new approach to learning video45;language representations by leveraging Large Language Models (LLMs). We repurpose pre45;trained LLMs to be conditioned on visual input and finetune them to create automatic video narrators. Our auto45;generated narrations offer a number of advantages including dense coverage of long videos better temporal synchronization of the visual information and text and much higher diversity of text. The video45;text embedding learned contrastively with these additional auto45;generated narrations outperforms the previous state45;of45;the45;art on multiple first45;person and third45;person video tasks both in zero45;shot and finetuned setups. Most notably LaViLa obtains an absolute gain of 10.137; on EGTEA classification and 5.937; Epic45;Kitchens45;100 multi45;instance retrieval benchmarks. Furthermore LaViLa trained with only half the narrations from the Ego4D dataset outperforms baseline models trained on the full set and shows positive scaling behavior on increasing pre45;training data and model size.
