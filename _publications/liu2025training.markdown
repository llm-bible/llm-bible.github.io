---
layout: publication
title: 'A Training-free LLM Framework With Interaction Between Contextually Related Subtasks In Solving Complex Tasks'
authors: Hongjia Liu, Jinlong Li
conference: "Arxiv"
year: 2025
bibkey: liu2025training
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.23053'}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'Applications', 'GPT']
---
Large language models (LLMs) have shown remarkable capabilities in solving
complex tasks. Recent work has explored decomposing such tasks into subtasks
with independent contexts. However, some contextually related subtasks may
encounter information loss during execution, leading to redundant operations or
execution failures. To address this issue, we propose a training-free framework
with an interaction mechanism, which enables a subtask to query specific
information or trigger certain actions in completed subtasks by sending
requests. To implement interaction, we introduce a subtask trajectory memory to
enable resumption of completed subtasks upon receiving interaction requests.
Additionally, we propose a new action during execution, which generates a
concise and precise description of execution process and outcomes of a subtask,
to assist subsequent subtasks in determining interaction targets and requests.
We evaluate our framework on interactive decision-making task WebShop and
multi-hop question answering HotpotQA, with GPT-3.5 and GPT-4, and comparison
results show that our framework outperforms the state-of-the-art training-free
baselines.
