---
layout: publication
title: 'Investigating The Effectiveness Of A Socratic Chain-of-thoughts Reasoning Method For Task Planning In Robotics, A Case Study'
authors: Veronica Bot, Zheyuan Xu
conference: "Arxiv"
year: 2025
bibkey: bot2025investigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.08174"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
Large language models (LLMs) have demonstrated unprecedented capability in
reasoning with natural language. Coupled with this development is the emergence
of embodied AI in robotics. Despite showing promise for verbal and written
reasoning tasks, it remains unknown whether LLMs are capable of navigating
complex spatial tasks with physical actions in the real world. To this end, it
is of interest to investigate applying LLMs to robotics in zero-shot learning
scenarios, and in the absence of fine-tuning - a feat which could significantly
improve human-robot interaction, alleviate compute cost, and eliminate
low-level programming tasks associated with robot tasks.
  To explore this question, we apply GPT-4(Omni) with a simulated Tiago robot
in Webots engine for an object search task. We evaluate the effectiveness of
three reasoning strategies based on Chain-of-Thought (CoT) sub-task list
generation with the Socratic method (SocraCoT) (in order of increasing rigor):
(1) Non-CoT/Non-SocraCoT, (2) CoT only, and (3) SocraCoT. Performance was
measured in terms of the proportion of tasks successfully completed and
execution time (N = 20). Our preliminary results show that when combined with
chain-of-thought reasoning, the Socratic method can be used for code generation
for robotic tasks that require spatial awareness. In extension of this finding,
we propose EVINCE-LoC; a modified EVINCE method that could further enhance
performance in highly complex and or dynamic testing scenarios.
