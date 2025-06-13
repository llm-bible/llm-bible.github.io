---
layout: publication
title: 'Brainstorming Brings Power To Large Language Models Of Knowledge Reasoning'
authors: Zining Qin, Chenhao Wang, Huiling Qin, Weijia Jia
conference: "Arxiv"
year: 2024
bibkey: qin2024brainstorming
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.06561"}
tags: ['Prompting', 'Ethics and Bias']
---
Large Language Models (LLMs) have demonstrated amazing capabilities in
language generation, text comprehension, and knowledge reasoning. While a
single powerful model can already handle multiple tasks, relying on a single
perspective can lead to biased and unstable results. Recent studies have
further improved the model's reasoning ability on a wide range of tasks by
introducing multi-model collaboration. However, models with different
capabilities may produce conflicting answers on the same problem, and how to
reasonably obtain the correct answer from multiple candidate models has become
a challenging problem. In this paper, we propose the multi-model brainstorming
based on prompt. It incorporates different models into a group for
brainstorming, and after multiple rounds of reasoning elaboration and
re-inference, a consensus answer is reached within the group. We conducted
experiments on three different types of datasets, and demonstrate that the
brainstorming can significantly improve the effectiveness in logical reasoning
and fact extraction. Furthermore, we find that two small-parameter models can
achieve accuracy approximating that of larger-parameter models through
brainstorming, which provides a new solution for distributed deployment of
LLMs.
