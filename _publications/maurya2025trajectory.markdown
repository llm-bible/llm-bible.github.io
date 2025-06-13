---
layout: publication
title: 'Trajectory Adaptation Using Large Language Models'
authors: Anurag Maurya, Tashmoy Ghosh, Ravi Prakash
conference: "Arxiv"
year: 2025
bibkey: maurya2025trajectory
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.12755"}
tags: ['Interpretability and Explainability', 'Training Techniques', 'Tools']
---
Adapting robot trajectories based on human instructions as per new situations
is essential for achieving more intuitive and scalable human-robot
interactions. This work proposes a flexible language-based framework to adapt
generic robotic trajectories produced by off-the-shelf motion planners like
RRT, A-star, etc, or learned from human demonstrations. We utilize pre-trained
LLMs to adapt trajectory waypoints by generating code as a policy for dense
robot manipulation, enabling more complex and flexible instructions than
current methods. This approach allows us to incorporate a broader range of
commands, including numerical inputs. Compared to state-of-the-art
feature-based sequence-to-sequence models which require training, our method
does not require task-specific training and offers greater interpretability and
more effective feedback mechanisms. We validate our approach through simulation
experiments on the robotic manipulator, aerial vehicle, and ground robot in the
Pybullet and Gazebo simulation environments, demonstrating that LLMs can
successfully adapt trajectories to complex human instructions.
