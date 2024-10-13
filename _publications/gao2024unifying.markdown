---
layout: publication
title: 'Unifying Demonstration Selection And Compression For In-context Learning'
authors: Gao Jun, Cao Ziqiang, Li Wenjie
conference: "Arxiv"
year: 2024
bibkey: gao2024unifying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.17062"}
tags: ['In Context Learning', 'Prompting', 'Tools']
---
In-context learning (ICL) facilitates large language models (LLMs) exhibiting
spectacular emergent capabilities in various scenarios. Unfortunately,
introducing demonstrations easily makes the prompt length explode, bringing a
significant burden to hardware. In addition, random demonstrations usually
achieve limited improvements in ICL, necessitating demonstration selection
among accessible candidates. Previous studies introduce extra modules to
perform demonstration compression or selection independently. In this paper, we
propose an ICL framework UniICL, which Unifies demonstration selection and
compression, and final response generation via a single frozen LLM.
Specifically, UniICL first projects actual demonstrations and inference text
inputs into short virtual tokens, respectively. Then, virtual tokens are
applied to select suitable demonstrations by measuring semantic similarity
within latent space among candidate demonstrations and inference input.
Finally, inference text inputs together with selected virtual demonstrations
are fed into the same frozen LLM for response generation. Notably, UniICL is a
parameter-efficient framework that only contains 17M trainable parameters
originating from the projection layer. We conduct experiments and analysis over
in- and out-domain datasets of both generative and understanding tasks,
encompassing ICL scenarios with plentiful and limited demonstration candidates.
Results show that UniICL effectively unifies \\(12 \times\\) compression,
demonstration selection, and response generation, efficiently scaling up the
baseline from 4-shot to 64-shot ICL in IMDb with 24 GB CUDA allocation
