---
layout: publication
title: 'SCREWS: A Modular Framework For Reasoning With Revisions'
authors: Kumar Shridhar, Harsh Jhamtani, Hao Fang, Benjamin Van Durme, Jason Eisner, Patrick Xia
conference: "Arxiv"
year: 2023
bibkey: shridhar2023modular
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2309.13075'}
tags: ['Model Architecture', 'Tools', 'Applications', 'Fine-Tuning', 'GPT']
---
Large language models (LLMs) can improve their accuracy on various tasks
through iteratively refining and revising their output based on feedback. We
observe that these revisions can introduce errors, in which case it is better
to roll back to a previous result. Further, revisions are typically
homogeneous: they use the same reasoning method that produced the initial
answer, which may not correct errors. To enable exploration in this space, we
present SCREWS, a modular framework for reasoning with revisions. It is
comprised of three main modules: Sampling, Conditional Resampling, and
Selection, each consisting of sub-modules that can be hand-selected per task.
We show that SCREWS not only unifies several previous approaches under a common
framework, but also reveals several novel strategies for identifying improved
reasoning chains. We evaluate our framework with state-of-the-art LLMs (ChatGPT
and GPT-4) on a diverse set of reasoning tasks and uncover useful new reasoning
strategies for each: arithmetic word problems, multi-hop question answering,
and code debugging. Heterogeneous revision strategies prove to be important, as
does selection between original and revised candidates.
