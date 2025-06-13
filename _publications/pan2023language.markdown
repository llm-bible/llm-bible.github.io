---
layout: publication
title: 'Langnav: Language As A Perceptual Representation For Navigation'
authors: Bowen Pan, Rameswar Panda, Souyoung Jin, Rogerio Feris, Aude Oliva, Phillip Isola, Yoon Kim
conference: "Arxiv"
year: 2023
bibkey: pan2023language
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2310.07889'}
tags: ['Agentic', 'GPT', 'Applications', 'Model Architecture', 'Prompting']
---
We explore the use of language as a perceptual representation for
vision-and-language navigation (VLN), with a focus on low-data settings. Our
approach uses off-the-shelf vision systems for image captioning and object
detection to convert an agent's egocentric panoramic view at each time step
into natural language descriptions. We then finetune a pretrained language
model to select an action, based on the current view and the trajectory
history, that would best fulfill the navigation instructions. In contrast to
the standard setup which adapts a pretrained language model to work directly
with continuous visual features from pretrained vision models, our approach
instead uses (discrete) language as the perceptual representation. We explore
several use cases of our language-based navigation (LangNav) approach on the
R2R VLN benchmark: generating synthetic trajectories from a prompted language
model (GPT-4) with which to finetune a smaller language model; domain transfer
where we transfer a policy learned on one simulated environment (ALFRED) to
another (more realistic) environment (R2R); and combining both vision- and
language-based representations for VLN. Our approach is found to improve upon
baselines that rely on visual features in settings where only a few expert
trajectories (10-100) are available, demonstrating the potential of language as
a perceptual representation for navigation.
