---
layout: publication
title: 'Astrollama-chat: Scaling Astrollama With Conversational And Diverse Datasets'
authors: Ernest Perkowski, Rui Pan, Tuan Dung Nguyen, Yuan-sen Ting, Sandor Kruk, Tong Zhang, Charlie O'neill, Maja Jablonska, Zechang Sun, Michael J. Smith, Huiling Liu, Kevin Schawinski, Kartheik Iyer, Ioana Ciucă For Universetbd
conference: "Arxiv"
year: 2024
bibkey: perkowski2024astrollama
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.01916"}
tags: ['Fine-Tuning', 'Pre-Training', 'GPT', 'Model Architecture', 'Training Techniques', 'Pretraining Methods']
---
We explore the potential of enhancing LLM performance in astronomy-focused
question-answering through targeted, continual pre-training. By employing a
compact 7B-parameter LLaMA-2 model and focusing exclusively on a curated set of
astronomy corpora -- comprising abstracts, introductions, and conclusions -- we
achieve notable improvements in specialized topic comprehension. While general
LLMs like GPT-4 excel in broader question-answering scenarios due to superior
reasoning capabilities, our findings suggest that continual pre-training with
limited resources can still enhance model performance on specialized topics.
Additionally, we present an extension of AstroLLaMA: the fine-tuning of the 7B
LLaMA model on a domain-specific conversational dataset, culminating in the
release of the chat-enabled AstroLLaMA for community use. Comprehensive
quantitative benchmarking is currently in progress and will be detailed in an
upcoming full paper. The model, AstroLLaMA-Chat, is now available at
https://huggingface.co/universeTBD, providing the first open-source
conversational AI tool tailored for the astronomy community.
