---
layout: publication
title: 'TWIST & SCOUT: Grounding Multimodal Llm-experts By Forget-free Tuning'
authors: Aritra Bhowmik, Mohammad Mahdi Derakhshani, Dennis Koelma, Yuki M. Asano, Martin R. Oswald, Cees G. M. Snoek
conference: "Arxiv"
year: 2024
bibkey: bhowmik2024twist
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.10491"}
tags: ['Tools', 'Multimodal Models']
---
Spatial awareness is key to enable embodied multimodal AI systems. Yet,
without vast amounts of spatial supervision, current Multimodal Large Language
Models (MLLMs) struggle at this task. In this paper, we introduce TWIST &
SCOUT, a framework that equips pre-trained MLLMs with visual grounding ability
without forgetting their existing image and language understanding skills. To
this end, we propose TWIST, a twin-expert stepwise tuning module that modifies
the decoder of the language model using one frozen module pre-trained on image
understanding tasks and another learnable one for visual grounding tasks. This
allows the MLLM to retain previously learned knowledge and skills, while
acquiring what is missing. To fine-tune the model effectively, we generate a
high-quality synthetic dataset we call SCOUT, which mimics human reasoning in
visual grounding. This dataset provides rich supervision signals, describing a
step-by-step multimodal reasoning process, thereby simplifying the task of
visual grounding. We evaluate our approach on several standard benchmark
datasets, encompassing grounded image captioning, zero-shot localization, and
visual grounding tasks. Our method consistently delivers strong performance
across all tasks, while retaining the pre-trained image understanding
capabilities.
