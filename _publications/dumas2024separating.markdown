---
layout: publication
title: 'Separating Tongue From Thought: Activation Patching Reveals Language-agnostic Concept Representations In Transformers'
authors: Clément Dumas, Chris Wendler, Veniamin Veselovsky, Giovanni Monea, Robert West
conference: "Arxiv"
year: 2024
bibkey: dumas2024separating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.08745"}
tags: ['Transformer', 'Model Architecture', 'Language Modeling', 'Reinforcement Learning', 'Pretraining Methods', 'Prompting']
---
A central question in multilingual language modeling is whether large
language models (LLMs) develop a universal concept representation, disentangled
from specific languages. In this paper, we address this question by analyzing
latent representations (latents) during a word translation task in
transformer-based LLMs. We strategically extract latents from a source
translation prompt and insert them into the forward pass on a target
translation prompt. By doing so, we find that the output language is encoded in
the latent at an earlier layer than the concept to be translated. Building on
this insight, we conduct two key experiments. First, we demonstrate that we can
change the concept without changing the language and vice versa through
activation patching alone. Second, we show that patching with the mean over
latents across different languages does not impair and instead improves the
models' performance in translating the concept. Our results provide evidence
for the existence of language-agnostic concept representations within the
investigated models.
