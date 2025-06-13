---
layout: publication
title: 'Abusing Images And Sounds For Indirect Instruction Injection In Multi-modal Llms'
authors: Eugene Bagdasaryan, Tsung-yin Hsieh, Ben Nassi, Vitaly Shmatikov
conference: "Arxiv"
year: 2023
bibkey: bagdasaryan2023abusing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2307.10490'}
tags: ['GPT', 'Security', 'Prompting', 'Model Architecture']
---
We demonstrate how images and sounds can be used for indirect prompt and
instruction injection in multi-modal LLMs. An attacker generates an adversarial
perturbation corresponding to the prompt and blends it into an image or audio
recording. When the user asks the (unmodified, benign) model about the
perturbed image or audio, the perturbation steers the model to output the
attacker-chosen text and/or make the subsequent dialog follow the attacker's
instruction. We illustrate this attack with several proof-of-concept examples
targeting LLaVa and PandaGPT.
