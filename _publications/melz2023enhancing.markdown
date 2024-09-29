---
layout: publication
title: 'Enhancing LLM Intelligence With ARM-RAG: Auxiliary Rationale Memory For Retrieval Augmented Generation'
authors: Melz Eric
conference: "Arxiv"
year: 2023
bibkey: melz2023enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.04177"}
tags: ['Fine Tuning', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Large Language Models (LLMs) are smart but forgetful. Recent studies (e.g. (Bubeck et al. 2023)) on modern LLMs have shown that they are capable of performing amazing tasks typically necessitating human-level intelligence. However unlike humans frozen LLMs do not improve over time; they neither acquire new knowledge nor learn from their successes or failures. Some approaches to improving the intelligence of LLMs include fine-tuning models based on problem-solving performance (Zelikman et al. 2022) and building bigger and more sophisticated models (Bubeck et al. 2023). However these methods have the drawback of requiring substantial data and computational resources to retrain existing models. In this paper we explore the use of Retrieval Augmented Generation also known as RAG (Lewis et al. 2021) to improve problem-solving performance. We propose ARM-RAG (Auxiliary Rationale Memory for Retrieval Augmented Generation) a system that learns from its successes without incurring high training costs. We demonstrate that the storage and subsequent retrieval of reasoning chains have a positive influence on performance in grade-school math problems.
