---
layout: publication
title: 'Speech-to-trajectory: Learning Human-like Verbal Guidance For Robot Motion'
authors: Eran Beeri Bamani, Eden Nissinman, Rotem Atari, Nevo Heimann Saadon, Avishai Sintov
conference: "Arxiv"
year: 2025
bibkey: bamani2025speech
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.05084'}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'Applications', 'GPT', 'Merging', 'Prompting']
---
Full integration of robots into real-life applications necessitates their
ability to interpret and execute natural language directives from untrained
users. Given the inherent variability in human language, equivalent directives
may be phrased differently, yet require consistent robot behavior. While Large
Language Models (LLMs) have advanced language understanding, they often falter
in handling user phrasing variability, rely on predefined commands, and exhibit
unpredictable outputs. This letter introduces the Directive Language Model
(DLM), a novel speech-to-trajectory framework that directly maps verbal
commands to executable motion trajectories, bypassing predefined phrases. DLM
utilizes Behavior Cloning (BC) on simulated demonstrations of human-guided
robot motion. To enhance generalization, GPT-based semantic augmentation
generates diverse paraphrases of training commands, labeled with the same
motion trajectory. DLM further incorporates a diffusion policy-based trajectory
generation for adaptive motion refinement and stochastic sampling. In contrast
to LLM-based methods, DLM ensures consistent, predictable motion without
extensive prompt engineering, facilitating real-time robotic guidance. As DLM
learns from trajectory data, it is embodiment-agnostic, enabling deployment
across diverse robotic platforms. Experimental results demonstrate DLM's
improved command generalization, reduced dependence on structured phrasing, and
achievement of human-like motion.
