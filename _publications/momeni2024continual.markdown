---
layout: publication
title: 'In-context Continual Learning Assisted By An External Continual Learner'
authors: Saleh Momeni, Sahisnu Mazumder, Zixuan Ke, Bing Liu
conference: "Arxiv"
year: 2024
bibkey: momeni2024continual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.15563"}
tags: ['Fine-Tuning', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Prompting', 'In-Context Learning']
---
Existing continual learning (CL) methods mainly rely on fine-tuning or
adapting large language models (LLMs). They still suffer from catastrophic
forgetting (CF). Little work has been done to exploit in-context learning (ICL)
to leverage the extensive knowledge within LLMs for CL without updating any
parameters. However, incrementally learning each new task in ICL necessitates
adding training examples from each class of the task to the prompt, which
hampers scalability as the prompt length increases. This issue not only leads
to excessively long prompts that exceed the input token limit of the underlying
LLM but also degrades the model's performance due to the overextended context.
To address this, we introduce InCA, a novel approach that integrates an
external continual learner (ECL) with ICL to enable scalable CL without CF. The
ECL is built incrementally to pre-select a small subset of likely classes for
each test instance. By restricting the ICL prompt to only these selected
classes, InCA prevents prompt lengths from becoming excessively long, while
maintaining high performance. Experimental results demonstrate that InCA
significantly outperforms existing CL baselines, achieving substantial
performance gains.
