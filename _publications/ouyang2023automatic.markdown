---
layout: publication
title: Autoplan Automatic Planning Of Interactive Decision45;making Tasks With Large Language Models
authors: Ouyang Siqi, Li Lei
conference: "Arxiv"
year: 2023
bibkey: ouyang2023automatic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.15064"}
  - {name: "Code", url: "https://github.com/owaski/AutoPlan"}
tags: ['Agentic', 'Has Code', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning']
---
Recent large language models (LLMs) are promising for making decisions in grounded environments. However LLMs frequently fail in complex decision45;making tasks due to the misalignment between the pre45;trained knowledge in LLMs and the actual rules in the environment. Existing methods require either costly gradient computation or lengthy in45;context demonstrations. In this paper we propose AutoPlan an approach to guide LLM45;based agents to accomplish interactive decision45;making tasks. AutoPlan augments the LLM prompt with a task45;solving plan and optimizes it through iterative experience collection and reflection. Our experiments show that AutoPlan though using no in45;context demonstrations achieves success rates on par with the baselines using human45;written demonstrations on ALFWorld and even outperforms them by 837; on HotpotQA. The code is available at https://github.com/owaski/AutoPlan.
