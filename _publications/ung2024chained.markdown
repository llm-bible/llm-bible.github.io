---
layout: publication
title: 'Chained Tuning Leads To Biased Forgetting'
authors: Megan Ung, Alicia Sun, Samuel J. Bell, Bhaktipriya Radharapu, Levent Sagun, Adina Williams
conference: "Arxiv"
year: 2024
bibkey: ung2024chained
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.16469"}
tags: ['Responsible AI', 'Ethics and Bias', 'Training Techniques', 'Reinforcement Learning']
---
Large language models (LLMs) are often fine-tuned for use on downstream
tasks, though this can degrade capabilities learned during previous training.
This phenomenon, often referred to as catastrophic forgetting, has important
potential implications for the safety of deployed models. In this work, we
first show that models trained on downstream tasks forget their safety tuning
to a greater extent than models trained in the opposite order. Second, we show
that forgetting disproportionately impacts safety information about certain
groups. To quantify this phenomenon, we define a new metric we term biased
forgetting. We conduct a systematic evaluation of the effects of task ordering
on forgetting and apply mitigations that can help the model recover from the
forgetting observed. We hope our findings can better inform methods for
chaining the finetuning of LLMs in continual learning settings to enable
training of safer and less toxic models.
