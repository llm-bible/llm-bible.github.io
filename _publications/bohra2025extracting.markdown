---
layout: publication
title: 'Weblists: Extracting Structured Information From Complex Interactive Websites Using Executable LLM Agents'
authors: Arth Bohra, Manvel Saroyan, Danil Melkozerov, Vahe Karufanyan, Gabriel Maher, Pascal Weinberger, Artem Harutyunyan, Giovanni Campagna
conference: "Arxiv"
year: 2025
bibkey: bohra2025extracting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.12682'}
tags: ['Agentic', 'Tools']
---
Most recent web agent research has focused on navigation and transaction
tasks, with little emphasis on extracting structured data at scale. We present
WebLists, a benchmark of 200 data-extraction tasks across four common business
and enterprise use-cases. Each task requires an agent to navigate to a webpage,
configure it appropriately, and extract complete datasets with well-defined
schemas. We show that both LLMs with search capabilities and SOTA web agents
struggle with these tasks, with a recall of 3% and 31%, respectively, despite
higher performance on question-answering tasks.
  To address this challenge, we propose BardeenAgent, a novel framework that
enables web agents to convert their execution into repeatable programs, and
replay them at scale across pages with similar structure. BardeenAgent is also
the first LLM agent to take advantage of the regular structure of HTML. In
particular BardeenAgent constructs a generalizable CSS selector to capture all
relevant items on the page, then fits the operations to extract the data.
  On the WebLists benchmark, BardeenAgent achieves 66% recall overall, more
than doubling the performance of SOTA web agents, and reducing cost per output
row by 3x.
