---
layout: publication
title: 'Autoplan: Automatic Planning Of Interactive Decision-making Tasks With Large Language Models'
authors: Ouyang Siqi, Li Lei
conference: "Arxiv"
year: 2023
bibkey: ouyang2023automatic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.15064"}
  - {name: "Code", url: "https://github.com/owaski/AutoPlan"}
tags: ['Agentic', 'Has Code', 'Prompting', 'Reinforcement Learning']
---
Recent large language models (LLMs) are promising for making decisions in
grounded environments. However, LLMs frequently fail in complex decision-making
tasks due to the misalignment between the pre-trained knowledge in LLMs and the
actual rules in the environment. Existing methods require either costly
gradient computation or lengthy in-context demonstrations. In this paper, we
propose AutoPlan, an approach to guide LLM-based agents to accomplish
interactive decision-making tasks. AutoPlan augments the LLM prompt with a
task-solving plan and optimizes it through iterative experience collection and
reflection. Our experiments show that AutoPlan, though using no in-context
demonstrations, achieves success rates on par with the baselines using
human-written demonstrations on ALFWorld and even outperforms them by 8% on
HotpotQA. The code is available at https://github.com/owaski/AutoPlan.
