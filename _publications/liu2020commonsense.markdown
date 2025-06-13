---
layout: publication
title: 'Commonsense Evidence Generation And Injection In Reading Comprehension'
authors: Ye Liu, Tao Yang, Zeyu You, Wei Fan, Philip S. Yu
conference: "Arxiv"
year: 2020
bibkey: liu2020commonsense
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2005.05240"}
tags: ['RAG', 'Applications', 'Tools']
---
Human tackle reading comprehension not only based on the given context itself
but often rely on the commonsense beyond. To empower the machine with
commonsense reasoning, in this paper, we propose a Commonsense Evidence
Generation and Injection framework in reading comprehension, named CEGI. The
framework injects two kinds of auxiliary commonsense evidence into
comprehensive reading to equip the machine with the ability of rational
thinking. Specifically, we build two evidence generators: the first generator
aims to generate textual evidence via a language model; the other generator
aims to extract factual evidence (automatically aligned text-triples) from a
commonsense knowledge graph after graph completion. Those evidences incorporate
contextual commonsense and serve as the additional inputs to the model.
Thereafter, we propose a deep contextual encoder to extract semantic
relationships among the paragraph, question, option, and evidence. Finally, we
employ a capsule network to extract different linguistic units (word and
phrase) from the relations, and dynamically predict the optimal option based on
the extracted units. Experiments on the CosmosQA dataset demonstrate that the
proposed CEGI model outperforms the current state-of-the-art approaches and
achieves the accuracy (83.6%) on the leaderboard.
