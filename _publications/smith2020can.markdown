---
layout: publication
title: 'Can You Put It All Together: Evaluating Conversational Agents'' Ability To
  Blend Skills'
authors: Eric Michael Smith, Mary Williamson, Kurt Shuster, Jason Weston, Y-lan Boureau
conference: Arxiv
year: 2020
citations: 36
bibkey: smith2020can
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.08449'}]
tags: [Ethics and Bias, Agentic, Model Architecture]
---
Being engaging, knowledgeable, and empathetic are all desirable general
qualities in a conversational agent. Previous work has introduced tasks and
datasets that aim to help agents to learn those qualities in isolation and
gauge how well they can express them. But rather than being specialized in one
single quality, a good open-domain conversational agent should be able to
seamlessly blend them all into one cohesive conversational flow. In this work,
we investigate several ways to combine models trained towards isolated
capabilities, ranging from simple model aggregation schemes that require
minimal additional training, to various forms of multi-task training that
encompass several skills at all training stages. We further propose a new
dataset, BlendedSkillTalk, to analyze how these capabilities would mesh
together in a natural conversation, and compare the performance of different
architectures and training schemes. Our experiments show that multi-tasking
over several tasks that focus on particular capabilities results in better
blended conversation performance compared to models trained on a single skill,
and that both unified or two-stage approaches perform well if they are
constructed to avoid unwanted bias in skill selection or are fine-tuned on our
new task.