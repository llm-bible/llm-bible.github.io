---
layout: publication
title: 'Llms Still Can''t Plan; Can Lrms? A Preliminary Evaluation Of Openai''s O1 On Planbench'
authors: Karthik Valmeekam, Kaya Stechly, Subbarao Kambhampati
conference: "Arxiv"
year: 2024
bibkey: valmeekam2024llms
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.13373'}
tags: ['Agentic', 'Efficiency and Optimization', 'GPT', 'Model Architecture', 'Pretraining Methods']
---
The ability to plan a course of action that achieves a desired state of
affairs has long been considered a core competence of intelligent agents and
has been an integral part of AI research since its inception. With the advent
of large language models (LLMs), there has been considerable interest in the
question of whether or not they possess such planning abilities. PlanBench, an
extensible benchmark we developed in 2022, soon after the release of GPT3, has
remained an important tool for evaluating the planning abilities of LLMs.
Despite the slew of new private and open source LLMs since GPT3, progress on
this benchmark has been surprisingly slow. OpenAI claims that their recent o1
(Strawberry) model has been specifically constructed and trained to escape the
normal limitations of autoregressive LLMs--making it a new kind of model: a
Large Reasoning Model (LRM). Using this development as a catalyst, this paper
takes a comprehensive look at how well current LLMs and new LRMs do on
PlanBench. As we shall see, while o1's performance is a quantum improvement on
the benchmark, outpacing the competition, it is still far from saturating it.
This improvement also brings to the fore questions about accuracy, efficiency,
and guarantees which must be considered before deploying such systems.
