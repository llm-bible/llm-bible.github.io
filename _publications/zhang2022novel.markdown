---
layout: publication
title: 'ET5: A Novel End-to-end Framework For Conversational Machine Reading Comprehension'
authors: Xiao Zhang, Heyan Huang, Zewen Chi, Xian-ling Mao
conference: "Arxiv"
year: 2022
bibkey: zhang2022novel
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2209.11484"}
  - {name: "Code", url: "https://github.com/Yottaxx/ET5"}
tags: ['Interpretability', 'Tools', 'Has Code', 'Reinforcement Learning']
---
Conversational machine reading comprehension (CMRC) aims to assist computers
to understand an natural language text and thereafter engage in a multi-turn
conversation to answer questions related to the text. Existing methods
typically require three steps: (1) decision making based on entailment
reasoning; (2) span extraction if required by the above decision; (3) question
rephrasing based on the extracted span. However, for nearly all these methods,
the span extraction and question rephrasing steps cannot fully exploit the
fine-grained entailment reasoning information in decision making step because
of their relative independence, which will further enlarge the information gap
between decision making and question phrasing. Thus, to tackle this problem, we
propose a novel end-to-end framework for conversational machine reading
comprehension based on shared parameter mechanism, called entailment reasoning
T5 (ET5). Despite the lightweight of our proposed framework, experimental
results show that the proposed ET5 achieves new state-of-the-art results on the
ShARC leaderboard with the BLEU-4 score of 55.2. Our model and code are
publicly available at https://github.com/Yottaxx/ET5.
