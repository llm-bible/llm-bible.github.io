---
layout: publication
title: 'Vision-language Models Create Cross-modal Task Representations'
authors: Grace Luo, Trevor Darrell, Amir Bar
conference: "Arxiv"
year: 2024
bibkey: luo2024vision
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.22330"}
tags: ['Multimodal Models', 'Model Architecture', 'GPT', 'Pretraining Methods', 'Prompting']
---
Autoregressive vision-language models (VLMs) can handle many tasks within a
single model, yet the representations that enable this capability remain
opaque. We find that VLMs align conceptually equivalent inputs into a shared
task vector, which is invariant to modality (text, image) and format (examples,
instruction), and may simplify VLM processing. We measure this alignment via
cross-modal transfer -- the ability of a task vector derived in one modality to
trigger the correct generation in another -- on a range of tasks and model
architectures. Although the task vector is highly compressed, we find that this
single vector outperforms prompting the model with the full task information,
unique to this cross-modal case. Furthermore, we show that task vectors can be
transferred from a base language model to its fine-tuned vision-language
counterpart, and that they can be derived solely from instructions without the
need for examples. Taken together, our findings shed light on how VLMs
internally process task information, and how they map different modalities into
common semantic representations. Project page:
https://vlm-cross-modal-reps.github.io.
