---
layout: publication
title: 'A Unified Framework For Motion Reasoning And Generation In Human Interaction'
authors: Jeongeun Park, Sungjoon Choi, Sangdoo Yun
conference: "Arxiv"
year: 2024
bibkey: park2024unified
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.05628"}
tags: ['Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'Merging', 'Fine-Tuning', 'Applications']
---
Recent advancements in large language models (LLMs) have significantly
improved their ability to generate natural and contextually relevant text,
enabling more human-like AI interactions. However, generating and understanding
interactive human-like motion, where multiple individuals engage in coordinated
movements, remains challenging due to the complexity of modeling these
interactions. Additionally, a unified and versatile model is needed to handle
diverse interactive scenarios, such as chat systems that dynamically adapt to
user instructions and assigned roles. To address these challenges, we introduce
VIM, the Versatile Interactive Motion-language model, which integrates both
language and motion modalities to effectively understand, generate, and control
interactive motions in multi-turn conversational contexts. Unlike previous
studies that primarily focus on uni-directional tasks such as text-to-motion or
motion-to-text, VIM employs a unified architecture capable of simultaneously
understanding and generating both motion and text modalities. Given the absence
of an appropriate dataset to support this task, we introduce Inter-MT2, a
large-scale instruction-tuning dataset containing 82.7K multi-turn interactive
motion instructions, covering 153K interactive motion samples. Inter-MT2 spans
diverse instructional scenarios, including motion editing, question answering,
and story generation, leveraging off-the-shelf large language models and motion
diffusion models to construct a broad set of interactive motion instructions.
We extensively evaluate the versatility of VIM across multiple interactive
motion-related tasks, including motion-to-text, text-to-motion, reaction
generation, motion editing, and reasoning about motion sequences.
