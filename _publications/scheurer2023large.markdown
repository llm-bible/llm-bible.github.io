---
layout: publication
title: 'Large Language Models Can Strategically Deceive Their Users When Put Under Pressure'
authors: Jérémy Scheurer, Mikita Balesni, Marius Hobbhahn
conference: "Arxiv"
year: 2023
bibkey: scheurer2023large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.07590"}
tags: ['Agentic', 'Training Techniques', 'GPT', 'Model Architecture']
---
We demonstrate a situation in which Large Language Models, trained to be
helpful, harmless, and honest, can display misaligned behavior and
strategically deceive their users about this behavior without being instructed
to do so. Concretely, we deploy GPT-4 as an agent in a realistic, simulated
environment, where it assumes the role of an autonomous stock trading agent.
Within this environment, the model obtains an insider tip about a lucrative
stock trade and acts upon it despite knowing that insider trading is
disapproved of by company management. When reporting to its manager, the model
consistently hides the genuine reasons behind its trading decision. We perform
a brief investigation of how this behavior varies under changes to the setting,
such as removing model access to a reasoning scratchpad, attempting to prevent
the misaligned behavior by changing system instructions, changing the amount of
pressure the model is under, varying the perceived risk of getting caught, and
making other simple changes to the environment. To our knowledge, this is the
first demonstration of Large Language Models trained to be helpful, harmless,
and honest, strategically deceiving their users in a realistic situation
without direct instructions or training for deception.
