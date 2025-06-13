---
layout: publication
title: 'ADAPT: Actively Discovering And Adapting To Preferences For Any Task'
authors: Maithili Patel, Xavier Puig, Ruta Desai, Roozbeh Mottaghi, Sonia Chernova, Joanne Truong, Akshara Rai
conference: "Arxiv"
year: 2025
bibkey: patel2025actively
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.04040'}
tags: ['Reinforcement Learning', 'Agentic', 'Training Techniques']
---
Assistive agents should be able to perform under-specified long-horizon tasks
while respecting user preferences. We introduce Actively Discovering and
Adapting to Preferences for any Task (ADAPT) -- a benchmark designed to
evaluate agents' ability to adhere to user preferences across various household
tasks through active questioning. Next, we propose Reflection-DPO, a novel
training approach for adapting large language models (LLMs) to the task of
active questioning. Reflection-DPO finetunes a 'student' LLM to follow the
actions of a privileged 'teacher' LLM, and optionally ask a question to gather
necessary information to better predict the teacher action. We find that prior
approaches that use state-of-the-art LLMs fail to sufficiently follow user
preferences in ADAPT due to insufficient questioning and poor adherence to
elicited preferences. In contrast, Reflection-DPO achieves a higher rate of
satisfying user preferences, outperforming a zero-shot chain-of-thought
baseline by 6.1% on unseen users.
