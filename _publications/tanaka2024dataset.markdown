---
layout: publication
title: 'Instructdoc: A Dataset For Zero-shot Generalization Of Visual Document Understanding With Instructions'
authors: Tanaka Ryota, Iki Taichi, Nishida Kyosuke, Saito Kuniko, Suzuki Jun
conference: "Arxiv"
year: 2024
bibkey: tanaka2024dataset
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.13313"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning', 'Training Techniques']
---
We study the problem of completing various visual document understanding (VDU) tasks e.g. question answering and information extraction on real-world documents through human-written instructions. To this end we propose InstructDoc the first large-scale collection of 30 publicly available VDU datasets each with diverse instructions in a unified format which covers a wide range of 12 tasks and includes open document types/formats. Furthermore to enhance the generalization performance on VDU tasks we design a new instruction-based document reading and understanding model InstructDr that connects document images image encoders and large language models (LLMs) through a trainable bridging module. Experiments demonstrate that InstructDr can effectively adapt to new VDU datasets tasks and domains via given instructions and outperforms existing multimodal LLMs and ChatGPT without specific training.
