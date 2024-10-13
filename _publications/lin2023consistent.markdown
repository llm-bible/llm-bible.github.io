---
layout: publication
title: 'Videodirectorgpt: Consistent Multi-scene Video Generation Via Llm-guided Planning'
authors: Lin Han, Zala Abhay, Cho Jaemin, Bansal Mohit
conference: "Arxiv"
year: 2023
bibkey: lin2023consistent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.15091"}
tags: ['GPT', 'Model Architecture', 'Prompting', 'RAG', 'Tools', 'Uncategorized']
---
Recent text-to-video (T2V) generation methods have seen significant
advancements. However, the majority of these works focus on producing short
video clips of a single event (i.e., single-scene videos). Meanwhile, recent
large language models (LLMs) have demonstrated their capability in generating
layouts and programs to control downstream visual modules. This prompts an
important question: can we leverage the knowledge embedded in these LLMs for
temporally consistent long video generation? In this paper, we propose
VideoDirectorGPT, a novel framework for consistent multi-scene video generation
that uses the knowledge of LLMs for video content planning and grounded video
generation. Specifically, given a single text prompt, we first ask our video
planner LLM (GPT-4) to expand it into a 'video plan', which includes the scene
descriptions, the entities with their respective layouts, the background for
each scene, and consistency groupings of the entities. Next, guided by this
video plan, our video generator, named Layout2Vid, has explicit control over
spatial layouts and can maintain temporal consistency of entities across
multiple scenes, while being trained only with image-level annotations. Our
experiments demonstrate that our proposed VideoDirectorGPT framework
substantially improves layout and movement control in both single- and
multi-scene video generation and can generate multi-scene videos with
consistency, while achieving competitive performance with SOTAs in open-domain
single-scene T2V generation. Detailed ablation studies, including dynamic
adjustment of layout control strength with an LLM and video generation with
user-provided images, confirm the effectiveness of each component of our
framework and its future potential.
