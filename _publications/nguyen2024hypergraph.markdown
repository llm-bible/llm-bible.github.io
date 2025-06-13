---
layout: publication
title: 'Hyperglm: Hypergraph For Video Scene Graph Generation And Anticipation'
authors: Trong-thuan Nguyen, Pha Nguyen, Jackson Cothren, Alper Yilmaz, Khoa Luu
conference: "Arxiv"
year: 2024
bibkey: nguyen2024hypergraph
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.18042"}
tags: ['Multimodal Models', 'Applications', 'Reinforcement Learning']
---
Multimodal LLMs have advanced vision-language tasks but still struggle with
understanding video scenes. To bridge this gap, Video Scene Graph Generation
(VidSGG) has emerged to capture multi-object relationships across video frames.
However, prior methods rely on pairwise connections, limiting their ability to
handle complex multi-object interactions and reasoning. To this end, we propose
Multimodal LLMs on a Scene HyperGraph (HyperGLM), promoting reasoning about
multi-way interactions and higher-order relationships. Our approach uniquely
integrates entity scene graphs, which capture spatial relationships between
objects, with a procedural graph that models their causal transitions, forming
a unified HyperGraph. Significantly, HyperGLM enables reasoning by injecting
this unified HyperGraph into LLMs. Additionally, we introduce a new Video Scene
Graph Reasoning (VSGR) dataset featuring 1.9M frames from third-person,
egocentric, and drone views and supports five tasks: Scene Graph Generation,
Scene Graph Anticipation, Video Question Answering, Video Captioning, and
Relation Reasoning. Empirically, HyperGLM consistently outperforms
state-of-the-art methods across five tasks, effectively modeling and reasoning
complex relationships in diverse video scenes.
