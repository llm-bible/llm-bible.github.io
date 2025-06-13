---
layout: publication
title: 'Taskgen: A Task-based, Memory-infused Agentic Framework Using Strictjson'
authors: John Chong Min Tan, Prince Saroj, Bharat Runwal, Hardik Maheshwari, Brian Lim Yi Sheng, Richard Cottrill, Alankrit Chona, Ambuj Kumar, Mehul Motani
conference: "Arxiv"
year: 2024
bibkey: tan2024task
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.15734"}
tags: ['Agentic', 'Tools', 'Reinforcement Learning', 'TACL', 'ACL']
---
TaskGen is an open-sourced agentic framework which uses an Agent to solve an
arbitrary task by breaking them down into subtasks. Each subtask is mapped to
an Equipped Function or another Agent to execute. In order to reduce verbosity
(and hence token usage), TaskGen uses StrictJSON that ensures JSON output from
the Large Language Model (LLM), along with additional features such as type
checking and iterative error correction. Key to the philosophy of TaskGen is
the management of information/memory on a need-to-know basis. We empirically
evaluate TaskGen on various environments such as 40x40 dynamic maze navigation
with changing obstacle locations (100% solve rate), TextWorld escape room
solving with dense rewards and detailed goals (96% solve rate), web browsing
(69% of actions successful), solving the MATH dataset (71% solve rate over 100
Level-5 problems), Retrieval Augmented Generation on NaturalQuestions dataset
(F1 score of 47.03%)
