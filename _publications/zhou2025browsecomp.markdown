---
layout: publication
title: 'Browsecomp-zh: Benchmarking Web Browsing Ability Of Large Language Models In Chinese'
authors: Peilin Zhou, Bruce Leon, Xiang Ying, Can Zhang, Yifan Shao, Qichen Ye, Dading Chong, Zhiling Jin, Chenxuan Xie, Meng Cao, Yuxin Gu, Sixin Hong, Jing Ren, Jian Chen, Chao Liu, Yining Hua
conference: "Arxiv"
year: 2025
bibkey: zhou2025browsecomp
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.19314'}
  - {name: "Code", url: 'https://github.com/PALIN2018/BrowseComp-ZH'}
tags: ['Reinforcement Learning', 'Agentic', 'Has Code']
---
As large language models (LLMs) evolve into tool-using agents, the ability to
browse the web in real-time has become a critical yardstick for measuring their
reasoning and retrieval competence. Existing benchmarks such as BrowseComp
concentrate on English and overlook the linguistic, infrastructural, and
censorship-related complexities of other major information ecosystems -- most
notably Chinese. To address this gap, we introduce BrowseComp-ZH, a
high-difficulty benchmark purpose-built to comprehensively evaluate LLM agents
on the Chinese web. BrowseComp-ZH consists of 289 multi-hop questions spanning
11 diverse domains. Each question is reverse-engineered from a short,
objective, and easily verifiable answer (e.g., a date, number, or proper noun).
A two-stage quality control protocol is applied to strive for high question
difficulty and answer uniqueness. We benchmark over 20 state-of-the-art
language models and agentic search systems on our proposed BrowseComp-ZH.
Despite their strong conversational and retrieval capabilities, most models
struggle severely: a large number achieve accuracy rates below 10%, and only a
handful exceed 20%. Even the best-performing system, OpenAI's DeepResearch,
reaches just 42.9%. These results demonstrate the considerable difficulty of
BrowseComp-ZH, where success demands not only effective retrieval strategies,
but also sophisticated reasoning and information reconciliation -- capabilities
that current models still struggle to master. Our dataset, construction
guidelines, and benchmark results have been publicly released at
https://github.com/PALIN2018/BrowseComp-ZH.
