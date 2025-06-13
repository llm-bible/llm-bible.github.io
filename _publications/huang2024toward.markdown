---
layout: publication
title: 'Toward Scene Graph And Layout Guided Complex 3D Scene Generation'
authors: Yu-hsiang Huang, Wei Wang, Sheng-yu Huang, Yu-chiang Frank Wang
conference: "Arxiv"
year: 2024
bibkey: huang2024toward
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.20473"}
tags: ['Tools', 'Efficiency and Optimization', 'Training Techniques', 'Prompting', 'Distillation']
---
Recent advancements in object-centric text-to-3D generation have shown
impressive results. However, generating complex 3D scenes remains an open
challenge due to the intricate relations between objects. Moreover, existing
methods are largely based on score distillation sampling (SDS), which
constrains the ability to manipulate multiobjects with specific interactions.
Addressing these critical yet underexplored issues, we present a novel
framework of Scene Graph and Layout Guided 3D Scene Generation (GraLa3D). Given
a text prompt describing a complex 3D scene, GraLa3D utilizes LLM to model the
scene using a scene graph representation with layout bounding box information.
GraLa3D uniquely constructs the scene graph with single-object nodes and
composite super-nodes. In addition to constraining 3D generation within the
desirable layout, a major contribution lies in the modeling of interactions
between objects in a super-node, while alleviating appearance leakage across
objects within such nodes. Our experiments confirm that GraLa3D overcomes the
above limitations and generates complex 3D scenes closely aligned with text
prompts.
