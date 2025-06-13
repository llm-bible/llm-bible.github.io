---
layout: publication
title: 'On-device Llms For Home Assistant: Dual Role In Intent Detection And Response Generation'
authors: Rune Birkmose, Nathan Mørkeberg Reece, Esben Hofstedt Norvin, Johannes Bjerva, Mike Zhang
conference: "Arxiv"
year: 2025
bibkey: birkmose2025llms
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.12923"}
tags: ['RAG', 'Prompting']
---
This paper investigates whether Large Language Models (LLMs), fine-tuned on
synthetic but domain-representative data, can perform the twofold task of (i)
slot and intent detection and (ii) natural language response generation for a
smart home assistant, while running solely on resource-limited, CPU-only edge
hardware. We fine-tune LLMs to produce both JSON action calls and text
responses. Our experiments show that 16-bit and 8-bit quantized variants
preserve high accuracy on slot and intent detection and maintain strong
semantic coherence in generated text, while the 4-bit model, while retaining
generative fluency, suffers a noticeable drop in device-service classification
accuracy. Further evaluations on noisy human (non-synthetic) prompts and
out-of-domain intents confirm the models' generalization ability, obtaining
around 80--86% accuracy. While the average inference time is 5--6 seconds per
query -- acceptable for one-shot commands but suboptimal for multi-turn
dialogue -- our results affirm that an on-device LLM can effectively unify
command interpretation and flexible response generation for home automation
without relying on specialized hardware.
