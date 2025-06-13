---
layout: publication
title: 'Multi-agent Large Language Models For Conversational Task-solving'
authors: Jonas Becker
conference: "Arxiv"
year: 2024
bibkey: becker2024multi
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.22932'}
tags: ['Agentic', 'Agent', 'RAG', 'Efficiency and Optimization', 'Fairness', 'Tools', 'Applications', 'Bias Mitigation', 'Ethics and Bias', 'Responsible AI']
---
In an era where single large language models have dominated the landscape of
artificial intelligence for years, multi-agent systems arise as new
protagonists in conversational task-solving. While previous studies have
showcased their potential in reasoning tasks and creative endeavors, an
analysis of their limitations concerning the conversational paradigms and the
impact of individual agents is missing. It remains unascertained how
multi-agent discussions perform across tasks of varying complexity and how the
structure of these conversations influences the process. To fill that gap, this
work systematically evaluates multi-agent systems across various discussion
paradigms, assessing their strengths and weaknesses in both generative tasks
and question-answering tasks. Alongside the experiments, I propose a taxonomy
of 20 multi-agent research studies from 2022 to 2024, followed by the
introduction of a framework for deploying multi-agent LLMs in conversational
task-solving. I demonstrate that while multi-agent systems excel in complex
reasoning tasks, outperforming a single model by leveraging expert personas,
they fail on basic tasks. Concretely, I identify three challenges that arise:
1) While longer discussions enhance reasoning, agents fail to maintain
conformity to strict task requirements, which leads to problem drift, making
shorter conversations more effective for basic tasks. 2) Prolonged discussions
risk alignment collapse, raising new safety concerns for these systems. 3) I
showcase discussion monopolization through long generations, posing the problem
of fairness in decision-making for tasks like summarization. This work uncovers
both the potential and challenges that arise with multi-agent interaction and
varying conversational paradigms, providing insights into how future research
could improve the efficiency, performance, and safety of multi-agent LLMs.
