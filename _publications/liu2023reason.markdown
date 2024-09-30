---
layout: publication
title: 'Reason For Future, Act For Now: A Principled Framework For Autonomous LLM Agents With Provable Sample Efficiency'
authors: Liu Zhihan, Hu Hao, Zhang Shenao, Guo Hongyi, Ke Shuqi, Liu Boyi, Wang Zhaoran
conference: "Arxiv"
year: 2023
bibkey: liu2023reason
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.17382"}
tags: ['Agentic', 'Efficiency And Optimization', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large language models (LLMs) demonstrate impressive reasoning abilities but translating reasoning into actions in the real world remains challenging. In particular it remains unclear how to complete a given task provably within a minimum number of interactions with the external environment e.g. through an internal mechanism of reasoning. To this end we propose a principled framework with provable regret guarantees to orchestrate reasoning and acting which we call reason for future act for now (textttRAFA). Specifically we design a prompt template for reasoning that learns from the memory buffer and plans a future trajectory over a long horizon (reason for future). At each step the LLM agent takes the initial action of the planned trajectory (act for now) stores the collected feedback in the memory buffer and reinvokes the reasoning routine to replan the future trajectory from the new state. The key idea is to cast reasoning in LLMs as learning and planning in Bayesian adaptive Markov decision processes (MDPs). Correspondingly we prompt LLMs to form an updated posterior of the unknown environment from the memory buffer (learning) and generate an optimal trajectory for multiple future steps that maximizes a value function (planning). The learning and planning subroutines are performed in an in-context manner to emulate the actor-critic update for MDPs. Our theoretical analysis proves that the novel combination of long-term reasoning and short-term acting achieves a () regret. Here (T) denotes the number of online interactions. In particular the regret bound highlights an intriguing interplay between the prior knowledge obtained through pretraining and the uncertainty reduction achieved by reasoning and acting. Our empirical validation shows that it outperforms various existing frameworks and achieves nearly perfect scores on a few benchmarks.
