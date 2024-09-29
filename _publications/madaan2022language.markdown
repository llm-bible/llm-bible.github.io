---
layout: publication
title: Language Models Of Code Are Few45;shot Commonsense Learners
authors: Aman Madaan, Shuyan Zhou, Uri Alon, Yiming Yang, Graham Neubig
conference: "Arxiv"
year: 2022
bibkey: madaan2022language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2210.07128v3"}
tags: ['Applications', 'GPT', 'Model Architecture']
---
We address the general task of structured commonsense reasoning given a natural language input the goal is to generate a graph such as an event 45;45; or a reasoning45;graph. To employ large language models (LMs) for this task existing approaches serialize the output graph as a flat list of nodes and edges. Although feasible these serialized graphs strongly deviate from the natural language corpora that LMs were pre45;trained on hindering LMs from generating them correctly. In this paper we show that when we instead frame structured commonsense reasoning tasks as code generation tasks pre45;trained LMs of code are better structured commonsense reasoners than LMs of natural language even when the downstream task does not involve source code at all. We demonstrate our approach across three diverse structured commonsense reasoning tasks. In all these natural language tasks we show that using our approach a code generation LM (CODEX) outperforms natural45;LMs that are fine45;tuned on the target task (e.g. T5) and other strong LMs such as GPT45;3 in the few45;shot setting.
