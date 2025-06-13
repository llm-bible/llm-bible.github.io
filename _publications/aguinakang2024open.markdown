---
layout: publication
title: 'Open-universe Indoor Scene Generation Using LLM Program Synthesis And Uncurated Object Databases'
authors: Rio Aguina-kang, Maxim Gumin, Do Heon Han, Stewart Morris, Seung Jean Yoo, Aditya Ganeshan, R. Kenny Jones, Qiuhong Anna Wei, Kailiang Fu, Daniel Ritchie
conference: "Arxiv"
year: 2024
bibkey: aguinakang2024open
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.09675"}
tags: ['Efficiency and Optimization', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Multimodal Models', 'Prompting']
---
We present a system for generating indoor scenes in response to text prompts.
The prompts are not limited to a fixed vocabulary of scene descriptions, and
the objects in generated scenes are not restricted to a fixed set of object
categories -- we call this setting indoor scene generation. Unlike most prior
work on indoor scene generation, our system does not require a large training
dataset of existing 3D scenes. Instead, it leverages the world knowledge
encoded in pre-trained large language models (LLMs) to synthesize programs in a
domain-specific layout language that describe objects and spatial relations
between them. Executing such a program produces a specification of a constraint
satisfaction problem, which the system solves using a gradient-based
optimization scheme to produce object positions and orientations. To produce
object geometry, the system retrieves 3D meshes from a database. Unlike prior
work which uses databases of category-annotated, mutually-aligned meshes, we
develop a pipeline using vision-language models (VLMs) to retrieve meshes from
massive databases of un-annotated, inconsistently-aligned meshes. Experimental
evaluations show that our system outperforms generative models trained on 3D
data for traditional, closed-universe scene generation tasks; it also
outperforms a recent LLM-based layout generation method on open-universe scene
generation.
