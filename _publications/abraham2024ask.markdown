---
layout: publication
title: 'To Ask Or Not To Ask? Detecting Absence Of Information In Vision And Language Navigation'
authors: Savitha Sam Abraham, Sourav Garg, Feras Dayoub
conference: "Arxiv"
year: 2024
bibkey: abraham2024ask
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.05831"}
tags: ['Agentic', 'Efficiency and Optimization', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Attention Mechanism', 'Multimodal Models']
---
Recent research in Vision Language Navigation (VLN) has overlooked the
development of agents' inquisitive abilities, which allow them to ask
clarifying questions when instructions are incomplete. This paper addresses how
agents can recognize "when" they lack sufficient information, without focusing
on "what" is missing, particularly in VLN tasks with vague instructions.
Equipping agents with this ability enhances efficiency by reducing potential
digressions and seeking timely assistance. The challenge in identifying such
uncertain points is balancing between being overly cautious (high recall) and
overly confident (high precision). We propose an attention-based
instruction-vagueness estimation module that learns associations between
instructions and the agent's trajectory. By leveraging instruction-to-path
alignment information during training, the module's vagueness estimation
performance improves by around 52% in terms of precision-recall balance. In our
ablative experiments, we also demonstrate the effectiveness of incorporating
this additional instruction-to-path attention network alongside the cross-modal
attention networks within the navigator module. Our results show that the
attention scores from the instruction-to-path attention network serve as better
indicators for estimating vagueness.
