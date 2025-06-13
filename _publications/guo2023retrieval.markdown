---
layout: publication
title: 'Retrieval-augmented Code Generation For Universal Information Extraction'
authors: Yucan Guo, Zixuan Li, Xiaolong Jin, Yantao Liu, Yutao Zeng, Wenxuan Liu, Xiang Li, Pan Yang, Long Bai, Jiafeng Guo, Xueqi Cheng
conference: "Arxiv"
year: 2023
bibkey: guo2023retrieval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.02962"}
tags: ['Tools', 'RAG', 'Prompting', 'Applications', 'In-Context Learning']
---
Information Extraction (IE) aims to extract structural knowledge (e.g.,
entities, relations, events) from natural language texts, which brings
challenges to existing methods due to task-specific schemas and complex text
expressions. Code, as a typical kind of formalized language, is capable of
describing structural knowledge under various schemas in a universal way. On
the other hand, Large Language Models (LLMs) trained on both codes and texts
have demonstrated powerful capabilities of transforming texts into codes, which
provides a feasible solution to IE tasks. Therefore, in this paper, we propose
a universal retrieval-augmented code generation framework based on LLMs, called
Code4UIE, for IE tasks. Specifically, Code4UIE adopts Python classes to define
task-specific schemas of various structural knowledge in a universal way. By so
doing, extracting knowledge under these schemas can be transformed into
generating codes that instantiate the predefined Python classes with the
information in texts. To generate these codes more precisely, Code4UIE adopts
the in-context learning mechanism to instruct LLMs with examples. In order to
obtain appropriate examples for different tasks, Code4UIE explores several
example retrieval strategies, which can retrieve examples semantically similar
to the given texts. Extensive experiments on five representative IE tasks
across nine datasets demonstrate the effectiveness of the Code4UIE framework.
