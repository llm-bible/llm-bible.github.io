---
layout: publication
title: 'Accessible Instruction-following Agent'
authors: Kairui Zhou
conference: "Arxiv"
year: 2023
bibkey: zhou2023accessible
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.06358"}
tags: ['Transformer', 'Agentic', 'GPT', 'Tools', 'Ethics and Bias', 'Applications', 'Model Architecture', 'Training Techniques', 'Pretraining Methods', 'Multimodal Models']
---
Humans can collaborate and complete tasks based on visual signals and
instruction from the environment. Training such a robot is difficult especially
due to the understanding of the instruction and the complicated environment.
Previous instruction-following agents are biased to English-centric corpus,
making it unrealizable to be applied to users that use multiple languages or
even low-resource languages. Nevertheless, the instruction-following agents are
pre-trained in a mode that assumes the user can observe the environment, which
limits its accessibility. In this work, we're trying to generalize the success
of instruction-following agents to non-English languages with little corpus
resources, and improve its intractability and accessibility. We introduce UVLN
(Universal Vision-Language Navigation), a novel machine-translation
instructional augmented framework for cross-lingual vision-language navigation,
with a novel composition of state-of-the-art large language model (GPT3) with
the image caption model (BLIP). We first collect a multilanguage
vision-language navigation dataset via machine translation. Then we extend the
standard VLN training objectives to a multilingual setting via a cross-lingual
language encoder. The alignment between different languages is captured through
a shared vision and action context via a cross-modal transformer, which encodes
the inputs of language instruction, visual observation, and action decision
sequences. To improve the intractability, we connect our agent with the large
language model that informs the situation and current state to the user and
also explains the action decisions. Experiments over Room Across Room Dataset
prove the effectiveness of our approach. And the qualitative results show the
promising intractability and accessibility of our instruction-following agent.
