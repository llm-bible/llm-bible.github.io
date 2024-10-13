---
layout: publication
title: 'Using Hallucinations To Bypass Gpt4''s Filter'
authors: Lemkin Benjamin
conference: "Arxiv"
year: 2024
bibkey: lemkin2024using
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.04769"}
tags: ['Agentic', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Security']
---
Large language models (LLMs) are initially trained on vast amounts of data,
then fine-tuned using reinforcement learning from human feedback (RLHF); this
also serves to teach the LLM to provide appropriate and safe responses. In this
paper, we present a novel method to manipulate the fine-tuned version into
reverting to its pre-RLHF behavior, effectively erasing the model's filters;
the exploit currently works for GPT4, Claude Sonnet, and (to some extent) for
Inflection-2.5. Unlike other jailbreaks (for example, the popular "Do Anything
Now" (DAN) ), our method does not rely on instructing the LLM to override its
RLHF policy; hence, simply modifying the RLHF process is unlikely to address
it. Instead, we induce a hallucination involving reversed text during which the
model reverts to a word bucket, effectively pausing the model's filter. We
believe that our exploit presents a fundamental vulnerability in LLMs currently
unaddressed, as well as an opportunity to better understand the inner workings
of LLMs during hallucinations.
