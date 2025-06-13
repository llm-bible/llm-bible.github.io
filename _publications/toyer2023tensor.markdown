---
layout: publication
title: 'Tensor Trust: Interpretable Prompt Injection Attacks From An Online Game'
authors: Sam Toyer, Olivia Watkins, Ethan Adrian Mendes, Justin Svegliato, Luke Bailey, Tiffany Wang, Isaac Ong, Karim Elmaaroufi, Pieter Abbeel, Trevor Darrell, Alan Ritter, Stuart Russell
conference: "Arxiv"
year: 2023
bibkey: toyer2023tensor
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.01011"}
  - {name: "Code", url: "https://tensortrust.ai/paper"}
tags: ['Security', 'Reinforcement Learning', 'Has Code', 'Prompting', 'Applications']
---
While Large Language Models (LLMs) are increasingly being used in real-world
applications, they remain vulnerable to prompt injection attacks: malicious
third party prompts that subvert the intent of the system designer. To help
researchers study this problem, we present a dataset of over 126,000 prompt
injection attacks and 46,000 prompt-based "defenses" against prompt injection,
all created by players of an online game called Tensor Trust. To the best of
our knowledge, this is currently the largest dataset of human-generated
adversarial examples for instruction-following LLMs. The attacks in our dataset
have a lot of easily interpretable stucture, and shed light on the weaknesses
of LLMs. We also use the dataset to create a benchmark for resistance to two
types of prompt injection, which we refer to as prompt extraction and prompt
hijacking. Our benchmark results show that many models are vulnerable to the
attack strategies in the Tensor Trust dataset. Furthermore, we show that some
attack strategies from the dataset generalize to deployed LLM-based
applications, even though they have a very different set of constraints to the
game. We release all data and source code at https://tensortrust.ai/paper
