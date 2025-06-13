---
layout: publication
title: 'Gitagent: Facilitating Autonomous Agent With Github By Tool Extension'
authors: Bohan Lyu, Xin Cong, Heyang Yu, Pan Yang, Yujia Qin, Yining Ye, Yaxi Lu, Zhong Zhang, Yukun Yan, Yankai Lin, Zhiyuan Liu, Maosong Sun
conference: "Arxiv"
year: 2023
bibkey: lyu2023facilitating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.17294"}
tags: ['Agentic', 'GPT', 'Tools', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Agent']
---
While Large Language Models (LLMs) like ChatGPT and GPT-4 have demonstrated
exceptional proficiency in natural language processing, their efficacy in
addressing complex, multifaceted tasks remains limited. A growing area of
research focuses on LLM-based agents equipped with external tools capable of
performing diverse tasks. However, existing LLM-based agents only support a
limited set of tools which is unable to cover a diverse range of user queries,
especially for those involving expertise domains. It remains a challenge for
LLM-based agents to extend their tools autonomously when confronted with
various user queries. As GitHub has hosted a multitude of repositories which
can be seen as a good resource for tools, a promising solution is that
LLM-based agents can autonomously integrate the repositories in GitHub
according to the user queries to extend their tool set. In this paper, we
introduce GitAgent, an agent capable of achieving the autonomous tool extension
from GitHub. GitAgent follows a four-phase procedure to incorporate
repositories and it can learn human experience by resorting to GitHub
Issues/PRs to solve problems encountered during the procedure. Experimental
evaluation involving 30 user queries demonstrates GitAgent's effectiveness,
achieving a 69.4% success rate on average.
