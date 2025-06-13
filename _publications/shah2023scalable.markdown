---
layout: publication
title: 'Scalable And Transferable Black-box Jailbreaks For Language Models Via Persona Modulation'
authors: Rusheb Shah, Quentin Feuillade--montixi, Soroush Pour, Arush Tagade, Stephen Casper, Javier Rando
conference: "Arxiv"
year: 2023
bibkey: shah2023scalable
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2311.03348'}
tags: ['GPT', 'Security', 'Prompting', 'Model Architecture']
---
Despite efforts to align large language models to produce harmless responses,
they are still vulnerable to jailbreak prompts that elicit unrestricted
behaviour. In this work, we investigate persona modulation as a black-box
jailbreaking method to steer a target model to take on personalities that are
willing to comply with harmful instructions. Rather than manually crafting
prompts for each persona, we automate the generation of jailbreaks using a
language model assistant. We demonstrate a range of harmful completions made
possible by persona modulation, including detailed instructions for
synthesising methamphetamine, building a bomb, and laundering money. These
automated attacks achieve a harmful completion rate of 42.5% in GPT-4, which is
185 times larger than before modulation (0.23%). These prompts also transfer to
Claude 2 and Vicuna with harmful completion rates of 61.0% and 35.9%,
respectively. Our work reveals yet another vulnerability in commercial large
language models and highlights the need for more comprehensive safeguards.
