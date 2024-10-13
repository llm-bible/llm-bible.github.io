---
layout: publication
title: 'Enhancing The Capability And Robustness Of Large Language Models Through Reinforcement Learning-driven Query Refinement'
authors: Huang Zisu, Wang Xiaohua, Zhang Feiran, Xu Zhibo, Zhang Cenyuan, Zheng Xiaoqing, Huang Xuanjing
conference: "Arxiv"
year: 2024
bibkey: huang2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.01461"}
  - {name: "Code", url: "https://github.com/Huangzisu/query-refinement"}
tags: ['Agentic', 'Has Code', 'Prompting', 'Reinforcement Learning', 'Security', 'Tools']
---
The capacity of large language models (LLMs) to generate honest, harmless,
and helpful responses heavily relies on the quality of user prompts. However,
these prompts often tend to be brief and vague, thereby significantly limiting
the full potential of LLMs. Moreover, harmful prompts can be meticulously
crafted and manipulated by adversaries to jailbreak LLMs, inducing them to
produce potentially toxic content. To enhance the capabilities of LLMs while
maintaining strong robustness against harmful jailbreak inputs, this study
proposes a transferable and pluggable framework that refines user prompts
before they are input into LLMs. This strategy improves the quality of the
queries, empowering LLMs to generate more truthful, benign and useful
responses. Specifically, a lightweight query refinement model is introduced and
trained using a specially designed reinforcement learning approach that
incorporates multiple objectives to enhance particular capabilities of LLMs.
Extensive experiments demonstrate that the refinement model not only improves
the quality of responses but also strengthens their robustness against
jailbreak attacks. Code is available at:
https://github.com/Huangzisu/query-refinement .
