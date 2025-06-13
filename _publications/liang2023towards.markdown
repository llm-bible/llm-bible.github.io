---
layout: publication
title: 'Drugchat: Towards Enabling Chatgpt-like Capabilities On Drug Molecule Graphs'
authors: Youwei Liang, Ruiyi Zhang, Li Zhang, Pengtao Xie
conference: "Arxiv"
year: 2023
bibkey: liang2023towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.03907"}
  - {name: "Code", url: "https://github.com/UCSD-AI4H/drugchat"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'GPT', 'Has Code']
---
A ChatGPT-like system for drug compounds could be a game-changer in
pharmaceutical research, accelerating drug discovery, enhancing our
understanding of structure-activity relationships, guiding lead optimization,
aiding drug repurposing, reducing the failure rate, and streamlining clinical
trials. In this work, we make an initial attempt towards enabling ChatGPT-like
capabilities on drug molecule graphs, by developing a prototype system
DrugChat. DrugChat works in a similar way as ChatGPT. Users upload a compound
molecule graph and ask various questions about this compound. DrugChat will
answer these questions in a multi-turn, interactive manner. The DrugChat system
consists of a graph neural network (GNN), a large language model (LLM), and an
adaptor. The GNN takes a compound molecule graph as input and learns a
representation for this graph. The adaptor transforms the graph representation
produced by the GNN into another representation that is acceptable to the LLM.
The LLM takes the compound representation transformed by the adaptor and users'
questions about this compound as inputs and generates answers. All these
components are trained end-to-end. To train DrugChat, we collected instruction
tuning datasets which contain 10,834 drug compounds and 143,517 question-answer
pairs. The code and data is available at
\url\{https://github.com/UCSD-AI4H/drugchat\}
