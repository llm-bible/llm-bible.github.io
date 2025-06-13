---
layout: publication
title: 'PILL: Plug Into LLM With Adapter Expert And Attention Gate'
authors: Fangyuan Zhang, Tingting Liang, Zhengyuan Wu, Yuyu Yin
conference: "Arxiv"
year: 2023
bibkey: zhang2023plug
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.02126"}
  - {name: "Code", url: "https://github.com/DsaltYfish/PILL"}
tags: ['Fine-Tuning', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Merging', 'Training Techniques', 'Attention Mechanism', 'Has Code', 'Pretraining Methods']
---
Due to the remarkable capabilities of powerful Large Language Models (LLMs)
in effectively following instructions, there has been a growing number of
assistants in the community to assist humans. Recently, significant progress
has been made in the development of Vision Language Models (VLMs), expanding
the capabilities of LLMs and enabling them to execute more diverse
instructions. However, it is foreseeable that models will likely need to handle
tasks involving additional modalities such as speech, video, and others. This
poses a particularly prominent challenge of dealing with the complexity of
mixed modalities. To address this, we introduce a novel architecture called
PILL: Plug Into LLM with adapter expert and attention gate to better decouple
these complex modalities and leverage efficient fine-tuning. We introduce two
modules: Firstly, utilizing Mixture-of-Modality-Adapter-Expert to independently
handle different modalities, enabling better adaptation to downstream tasks
while preserving the expressive capability of the original model. Secondly, by
introducing Modality-Attention-Gating, which enables adaptive control of the
contribution of modality tokens to the overall representation. In addition, we
have made improvements to the Adapter to enhance its learning and expressive
capabilities. Experimental results demonstrate that our approach exhibits
competitive performance compared to other mainstream methods for modality
fusion. For researchers interested in our work, we provide free access to the
code and models at https://github.com/DsaltYfish/PILL.
