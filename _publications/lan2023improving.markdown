---
layout: publication
title: Improving Zero45;shot Visual Question Answering Via Large Language Models With Reasoning Question Prompts
authors: Lan Yunshi, Li Xiang, Liu Xin, Li Yang, Qin Wei, Qian Weining
conference: "Arxiv"
year: 2023
bibkey: lan2023improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09050"}
  - {name: "Code", url: "https://github.com/ECNU&#45;DASE&#45;NLP/RQP&#125;"}
tags: ['Applications', 'Has Code', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Zero45;shot Visual Question Answering (VQA) is a prominent vision45;language task that examines both the visual and textual understanding capability of systems in the absence of training data. Recently by converting the images into captions information across multi45;modalities is bridged and Large Language Models (LLMs) can apply their strong zero45;shot generalization capability to unseen questions. To design ideal prompts for solving VQA via LLMs several studies have explored different strategies to select or generate question45;answer pairs as the exemplar prompts which guide LLMs to answer the current questions effectively. However they totally ignore the role of question prompts. The original questions in VQA tasks usually encounter ellipses and ambiguity which require intermediate reasoning. To this end we present Reasoning Question Prompts for VQA tasks which can further activate the potential of LLMs in zero45;shot scenarios. Specifically for each question we first generate self45;contained questions as reasoning question prompts via an unsupervised question edition module considering sentence fluency semantic integrity and syntactic invariance. Each reasoning question prompt clearly indicates the intent of the original question. This results in a set of candidate answers. Then the candidate answers associated with their confidence scores acting as answer heuristics are fed into LLMs and produce the final answer. We evaluate reasoning question prompts on three VQA challenges experimental results demonstrate that they can significantly improve the results of LLMs on zero45;shot setting and outperform existing state45;of45;the45;art zero45;shot methods on three out of four data sets. Our source code is publicly released at url123;https://github.com/ECNU&#45;DASE&#45;NLP/RQP&#125;.
