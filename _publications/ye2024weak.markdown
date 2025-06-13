---
layout: publication
title: 'Weak-to-strong Generalization Beyond Accuracy: A Pilot Study In Safety, Toxicity, And Legal Reasoning'
authors: Ruimeng Ye, Yang Xiao, Bo Hui
conference: "Arxiv"
year: 2024
bibkey: ye2024weak
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.12621"}
  - {name: "Code", url: "https://github.com/yeruimeng/WTS.git"}
tags: ['Responsible AI', 'Has Code']
---
As large language models (LLMs) continue to advance, ensuring their alignment
with human values becomes increasingly critical. Traditional alignment methods
heavily rely on human feedback to fine-tune models. With the emergence of
superhuman models whose outputs may surpass human understanding, evaluating and
aligning these models using human judgments poses significant challenges. To
address the challenges, recent works use weak supervisors to elicit knowledge
from much stronger models. However, there are important disanalogies between
the empirical setup in the existing works and the genuine goal of alignment. We
remark that existing works investigate the phenomenon of weak-to-strong
generation in analogous setup (i.e., binary classification), rather than
practical alignment-relevant tasks (e.g., safety). In this paper, we bridge
this gap by extending weak-to-strong generation to the context of practical
alignment. We empirically demonstrate the widespread phenomenon of
weak-to-strong generation in three complicated alignment tasks: safety,
toxicity, and legal reasoning\}. Furthermore, we explore efficient strategies
for improving alignment performance to enhance the quality of model outcomes.
Lastly, we summarize and analyze the challenges and potential solutions in
regard to specific alignment tasks, which we hope to catalyze the research
progress on the topic of weak-to-strong generalization. Our code is released at
https://github.com/yeruimeng/WTS.git.
