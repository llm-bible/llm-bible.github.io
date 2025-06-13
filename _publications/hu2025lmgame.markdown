---
layout: publication
title: 'Lmgame-bench: How Good Are Llms At Playing Games?'
authors: Lanxiang Hu, Mingjia Huo, Yuxuan Zhang, Haoyang Yu, Eric P. Xing, Ion Stoica, Tajana Rosing, Haojian Jin, Hao Zhang
conference: "Arxiv"
year: 2025
bibkey: hu2025lmgame
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.15146"}
  - {name: "Code", url: "https://github.com/lmgame-org/GamingAgent/lmgame-bench"}
tags: ['Agentic', 'Tools', 'Reinforcement Learning', 'Has Code', 'Prompting']
---
Playing video games requires perception, memory, and planning, exactly the faculties modern large language model (LLM) agents are expected to master. We study the major challenges in using popular video games to evaluate modern LLMs and find that directly dropping LLMs into games cannot make an effective evaluation, for three reasons -- brittle vision perception, prompt sensitivity, and potential data contamination. We introduce lmgame-Bench to turn games into reliable evaluations. lmgame-Bench features a suite of platformer, puzzle, and narrative games delivered through a unified Gym-style API and paired with lightweight perception and memory scaffolds, and is designed to stabilize prompt variance and remove contamination. Across 13 leading models, we show lmgame-Bench is challenging while still separating models well. Correlation analysis shows that every game probes a unique blend of capabilities often tested in isolation elsewhere. More interestingly, performing reinforcement learning on a single game from lmgame-Bench transfers both to unseen games and to external planning tasks. Our evaluation code is available at https://github.com/lmgame-org/GamingAgent/lmgame-bench.
