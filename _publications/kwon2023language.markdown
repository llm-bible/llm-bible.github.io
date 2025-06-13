---
layout: publication
title: 'Language Models As Zero-shot Trajectory Generators'
authors: Teyun Kwon, Norman Di Palo, Edward Johns
conference: "IEEE Robotics and Automation Letters (Volume 9 Issue 7 July 2024 Pages 6728-6735)"
year: 2023
bibkey: kwon2023language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.11604"}
  - {name: "Code", url: "https://www.robot-learning.uk/language-models-trajectory-generators"}
tags: ['GPT', 'Model Architecture', 'Reinforcement Learning', 'Has Code', 'Prompting']
---
Large Language Models (LLMs) have recently shown promise as high-level
planners for robots when given access to a selection of low-level skills.
However, it is often assumed that LLMs do not possess sufficient knowledge to
be used for the low-level trajectories themselves. In this work, we address
this assumption thoroughly, and investigate if an LLM (GPT-4) can directly
predict a dense sequence of end-effector poses for manipulation tasks, when
given access to only object detection and segmentation vision models. We
designed a single, task-agnostic prompt, without any in-context examples,
motion primitives, or external trajectory optimisers. Then we studied how well
it can perform across 30 real-world language-based tasks, such as "open the
bottle cap" and "wipe the plate with the sponge", and we investigated which
design choices in this prompt are the most important. Our conclusions raise the
assumed limit of LLMs for robotics, and we reveal for the first time that LLMs
do indeed possess an understanding of low-level robot control sufficient for a
range of common tasks, and that they can additionally detect failures and then
re-plan trajectories accordingly. Videos, prompts, and code are available at:
https://www.robot-learning.uk/language-models-trajectory-generators.
