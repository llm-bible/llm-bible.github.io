---
layout: publication
title: 'In-context Imitation Learning Via Next-token Prediction'
authors: Letian Fu, Huang Huang, Gaurav Datta, Lawrence Yunliang Chen, William Chung-ho Panitch, Fangchen Liu, Hui Li, Ken Goldberg
conference: "Arxiv"
year: 2024
bibkey: fu2024imitation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.15980"}
  - {name: "Code", url: "https://icrt.dev/"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'GPT', 'Pretraining Methods', 'Transformer', 'Has Code', 'Prompting']
---
We explore how to enhance next-token prediction models to perform in-context
imitation learning on a real robot, where the robot executes new tasks by
interpreting contextual information provided during the input phase, without
updating its underlying policy parameters. We propose In-Context Robot
Transformer (ICRT), a causal transformer that performs autoregressive
prediction on sensorimotor trajectories without relying on any linguistic data
or reward function. This formulation enables flexible and training-free
execution of new tasks at test time, achieved by prompting the model with
sensorimotor trajectories of the new task composing of image observations,
actions and states tuples, collected through human teleoperation. Experiments
with a Franka Emika robot demonstrate that the ICRT can adapt to new tasks
specified by prompts, even in environment configurations that differ from both
the prompt and the training data. In a multitask environment setup, ICRT
significantly outperforms current state-of-the-art next-token prediction models
in robotics on generalizing to unseen tasks. Code, checkpoints and data are
available on https://icrt.dev/
