---
layout: publication
title: LLMs Cant Plan But Can Help Planning in LLM-Modulo Frameworks
authors: Kambhampati Subbarao, Valmeekam Karthik, Guan Lin, Verma Mudit, Stechly Kaya, Bhambri Siddhant, Saldyt Lucas, Murthy Anil
conference: "Proceedings of the"
year: 2024
bibkey: kambhampati2024llms
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.01817"}
tags: ['LLM', 'Merging', 'Pretraining Methods', 'Tools']
---
There is considerable confusion about the role of Large Language Models (LLMs) in planning and reasoning tasks. On one side are over-optimistic claims that LLMs can indeed do these tasks with just the right prompting or self-verification strategies. On the other side are perhaps over-pessimistic claims that all that LLMs are good for in planning/reasoning tasks are as mere translators of the problem specification from one syntactic format to another and ship the problem off to external symbolic solvers. In this position paper we take the view that both these extremes are misguided. We argue that auto-regressive LLMs cannot by themselves do planning or self-verification (which is after all a form of reasoning) and shed some light on the reasons for misunderstandings in the literature. We will also argue that LLMs should be viewed as universal approximate knowledge sources that have much more meaningful roles to play in planning/reasoning tasks beyond simple front-end/back-end format translators. We present a vision of bf LLM-Modulo Frameworks that combine the strengths of LLMs with external model-based verifiers in a tighter bi-directional interaction regime. We will show how the models driving the external verifiers themselves can be acquired with the help of LLMs. We will also argue that rather than simply pipelining LLMs and symbolic components this LLM-Modulo Framework provides a better neuro-symbolic approach that offers tighter integration between LLMs and symbolic components and allows extending the scope of model-based planning/reasoning regimes towards more flexible knowledge problem and preference specifications.
