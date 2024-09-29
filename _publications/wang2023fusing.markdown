---
layout: publication
title: FIAT Fusing Learning Paradigms With Instruction45;accelerated Tuning
authors: Wang Xinyi, Wieting John, Clark Jonathan H.
conference: "Arxiv"
year: 2023
bibkey: wang2023fusing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.04663"}
tags: ['Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Learning paradigms for large language models (LLMs) currently tend to fall within either in45;context learning (ICL) or full fine45;tuning. Each of these comes with their own trade45;offs based on available data model size compute cost ease45;of45;use and final quality with neither solution performing well across45;the45;board. In this article we first describe ICL and fine45;tuning paradigms in a way that highlights their natural connections. Based on these connections we propose a new learning paradigm called FIAT that fuses the best of these paradigms together enabling prompt45;engineered instructions and chain45;of45;thought reasoning with the very largest models while also using similar methods to perform parameter updates on a modestly45;sized LLM with parameter45;efficient tuning. We evaluate FIATs effectiveness on a variety of multilingual tasks and observe that FIAT performs better than both ICL and fine45;tuning at scales ranging from 10045;10000 training examples. We hope that FIAT provides a practical way of harnessing the full potential of LLMs without needing to make a hard choice between learning paradigms.
