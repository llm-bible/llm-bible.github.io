---
layout: publication
title: 'Embodied-rag: General Non-parametric Embodied Memory For Retrieval And Generation'
authors: Quanting Xie, So Yeon Min, Pengliang Ji, Yue Yang, Tianyi Zhang, Kedi Xu, Aarav Bajaj, Ruslan Salakhutdinov, Matthew Johnson-roberson, Yonatan Bisk
conference: "Arxiv"
year: 2024
bibkey: xie2024embodied
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.18313"}
tags: ['Agentic', 'Multimodal Models', 'Tools', 'RAG', 'Interpretability and Explainability']
---
There is no limit to how much a robot might explore and learn, but all of
that knowledge needs to be searchable and actionable. Within language research,
retrieval augmented generation (RAG) has become the workhorse of large-scale
non-parametric knowledge; however, existing techniques do not directly transfer
to the embodied domain, which is multimodal, where data is highly correlated,
and perception requires abstraction. To address these challenges, we introduce
Embodied-RAG, a framework that enhances the foundational model of an embodied
agent with a non-parametric memory system capable of autonomously constructing
hierarchical knowledge for both navigation and language generation.
Embodied-RAG handles a full range of spatial and semantic resolutions across
diverse environments and query types, whether for a specific object or a
holistic description of ambiance. At its core, Embodied-RAG's memory is
structured as a semantic forest, storing language descriptions at varying
levels of detail. This hierarchical organization allows the system to
efficiently generate context-sensitive outputs across different robotic
platforms. We demonstrate that Embodied-RAG effectively bridges RAG to the
robotics domain, successfully handling over 250 explanation and navigation
queries across kilometer-level environments, highlighting its promise as a
general-purpose non-parametric system for embodied agents.
