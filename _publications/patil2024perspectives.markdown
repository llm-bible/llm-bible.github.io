---
layout: publication
title: Goex: Perspectives And Designs Towards A Runtime For Autonomous LLM Applications
authors: Patil Shishir G., Zhang Tianjun, Fang Vivian, C. Noppapon, Huang Roy, Hao Aaron, Casado Martin, Gonzalez Joseph E., Popa Raluca Ada, Stoica Ion
conference: "Arxiv"
year: 2024
bibkey: patil2024perspectives
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.06921"}
  - {name: "Code", url: "https://github.com/ShishirPatil/gorilla/"}
tags: ['Agentic', 'Applications', 'Has Code', 'Reinforcement Learning', 'Tools']
---
Large Language Models (LLMs) are evolving beyond their classical role of providing information within dialogue systems to actively engaging with tools and performing actions on real-world applications and services. Today humans verify the correctness and appropriateness of the LLM-generated outputs (e.g. code functions or actions) before putting them into real-world execution. This poses significant challenges as code comprehension is well known to be notoriously difficult. In this paper we study how humans can efficiently collaborate with delegate to and supervise autonomous LLMs in the future. We argue that in many cases post-facto validation - verifying the correctness of a proposed action after seeing the output - is much easier than the aforementioned pre-facto validation setting. The core concept behind enabling a post-facto validation system is the integration of an intuitive undo feature and establishing a damage confinement for the LLM-generated actions as effective strategies to mitigate the associated risks. Using this a human can now either revert the effect of an LLM-generated output or be confident that the potential risk is bounded. We believe this is critical to unlock the potential for LLM agents to interact with applications and services with limited (post-facto) human involvement. We describe the design and implementation of our open-source runtime for executing LLM actions Gorilla Execution Engine (GoEX) and present open research questions towards realizing the goal of LLMs and applications interacting with each other with minimal human supervision. We release GoEX at https://github.com/ShishirPatil/gorilla/."
