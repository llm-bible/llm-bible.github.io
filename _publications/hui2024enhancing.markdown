---
layout: publication
title: 'Rot: Enhancing Large Language Models With Reflection On Search Trees'
authors: Hui Wenyang, Tu Kewei
conference: "Arxiv"
year: 2024
bibkey: hui2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.05449"}
tags: ['Prompting', 'Tools', 'Uncategorized']
---
Large language models (LLMs) have demonstrated impressive capability in
reasoning and planning when integrated with tree-search-based prompting
methods. However, since these methods ignore the previous search experiences,
they often make the same mistakes in the search process. To address this issue,
we introduce Reflection on search Trees (RoT), an LLM reflection framework
designed to improve the performance of tree-search-based prompting methods. It
uses a strong LLM to summarize guidelines from previous tree search experiences
to enhance the ability of a weak LLM. The guidelines are instructions about
solving this task through tree search which can prevent the weak LLMs from
making similar mistakes in the past search process. In addition, we proposed a
novel state selection method, which identifies the critical information from
historical search processes to help RoT generate more specific and meaningful
guidelines. In our extensive experiments, we find that RoT significantly
improves the performance of LLMs in reasoning or planning tasks with various
tree-search-based prompting methods (e.g., BFS and MCTS). Non-tree-search-based
prompting methods such as Chain-of-Thought (CoT) can also benefit from RoT
guidelines since RoT can provide task-specific knowledge collected from the
search experience.
