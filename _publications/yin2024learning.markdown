---
layout: publication
title: 'In-context Learning Enables Robot Action Prediction In Llms'
authors: Yida Yin, Zekai Wang, Yuvan Sharma, Dantong Niu, Trevor Darrell, Roei Herzig
conference: "Arxiv"
year: 2024
bibkey: yin2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.12782"}
tags: ['Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Prompting', 'In-Context Learning']
---
Recently, Large Language Models (LLMs) have achieved remarkable success using
in-context learning (ICL) in the language domain. However, leveraging the ICL
capabilities within LLMs to directly predict robot actions remains largely
unexplored. In this paper, we introduce RoboPrompt, a framework that enables
off-the-shelf text-only LLMs to directly predict robot actions through ICL
without training. Our approach first heuristically identifies keyframes that
capture important moments from an episode. Next, we extract end-effector
actions from these keyframes as well as the estimated initial object poses, and
both are converted into textual descriptions. Finally, we construct a
structured template to form ICL demonstrations from these textual descriptions
and a task instruction. This enables an LLM to directly predict robot actions
at test time. Through extensive experiments and analysis, RoboPrompt shows
stronger performance over zero-shot and ICL baselines in simulated and
real-world settings. Our project page is available at
https://davidyyd.github.io/roboprompt.
