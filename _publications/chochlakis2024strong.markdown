---
layout: publication
title: 'The Strong Pull Of Prior Knowledge In Large Language Models And Its Impact On Emotion Recognition'
authors: Georgios Chochlakis, Alexandros Potamianos, Kristina Lerman, Shrikanth Narayanan
conference: "2024 12th International Conference on Affective Computing and Intelligent Interaction (ACII). IEEE 2024"
year: 2024
bibkey: chochlakis2024strong
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.17125"}
tags: ['Pre-Training', 'Training Techniques', 'Few-Shot', 'Prompting', 'In-Context Learning']
---
In-context Learning (ICL) has emerged as a powerful paradigm for performing
natural language tasks with Large Language Models (LLM) without updating the
models' parameters, in contrast to the traditional gradient-based finetuning.
The promise of ICL is that the LLM can adapt to perform the present task at a
competitive or state-of-the-art level at a fraction of the cost. The ability of
LLMs to perform tasks in this few-shot manner relies on their background
knowledge of the task (or task priors). However, recent work has found that,
unlike traditional learning, LLMs are unable to fully integrate information
from demonstrations that contrast task priors. This can lead to performance
saturation at suboptimal levels, especially for subjective tasks such as
emotion recognition, where the mapping from text to emotions can differ widely
due to variability in human annotations. In this work, we design experiments
and propose measurements to explicitly quantify the consistency of proxies of
LLM priors and their pull on the posteriors. We show that LLMs have strong yet
inconsistent priors in emotion recognition that ossify their predictions. We
also find that the larger the model, the stronger these effects become. Our
results suggest that caution is needed when using ICL with larger LLMs for
affect-centered tasks outside their pre-training domain and when interpreting
ICL results.
