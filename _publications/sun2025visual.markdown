---
layout: publication
title: 'Visual Intention Grounding For Egocentric Assistants'
authors: Pengzhan Sun, Junbin Xiao, Tze Ho Elden Tse, Yicong Li, Arjun Akula, Angela Yao
conference: "Arxiv"
year: 2025
bibkey: sun2025visual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.13621"}
tags: ['Multimodal Models', 'Training Techniques', 'Applications']
---
Visual grounding associates textual descriptions with objects in an image.
Conventional methods target third-person image inputs and named object queries.
In applications such as AI assistants, the perspective shifts -- inputs are
egocentric, and objects may be referred to implicitly through needs and
intentions. To bridge this gap, we introduce EgoIntention, the first dataset
for egocentric visual intention grounding. EgoIntention challenges multimodal
LLMs to 1) understand and ignore unintended contextual objects and 2) reason
about uncommon object functionalities. Benchmark results show that current
models misidentify context objects and lack affordance understanding in
egocentric views. We also propose Reason-to-Ground (RoG) instruction tuning; it
enables hybrid training with normal descriptions and egocentric intentions with
a chained intention reasoning and object grounding mechanism. RoG significantly
outperforms naive finetuning and hybrid training on EgoIntention, while
maintaining or slightly improving naive description grounding. This advancement
enables unified visual grounding for egocentric and exocentric visual inputs
while handling explicit object queries and implicit human intentions.
