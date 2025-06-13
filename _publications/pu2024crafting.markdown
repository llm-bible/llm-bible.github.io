---
layout: publication
title: 'Crafting A Good Prompt Or Providing Exemplary Dialogues? A Study Of In-context Learning For Persona-based Dialogue Generation'
authors: Jiashu Pu, Yajing Wan, Yuru Zhang, Jing Chen, Ling Cheng, Qian Shao, Yongzhu Chang, Tangjie Lv, Rongsheng Zhang
conference: "Arxiv"
year: 2024
bibkey: pu2024crafting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.09954"}
tags: ['Interpretability and Explainability', 'Applications', 'Prompting', 'In-Context Learning']
---
Previous in-context learning (ICL) research has focused on tasks such as
classification, machine translation, text2table, etc., while studies on whether
ICL can improve human-like dialogue generation are scarce. Our work fills this
gap by systematically investigating the ICL capabilities of large language
models (LLMs) in persona-based dialogue generation, conducting extensive
experiments on high-quality real human Chinese dialogue datasets. From
experimental results, we draw three conclusions: 1) adjusting prompt
instructions is the most direct, effective, and economical way to improve
generation quality; 2) randomly retrieving demonstrations (demos) achieves the
best results, possibly due to the greater diversity and the amount of effective
information; counter-intuitively, retrieving demos with a context identical to
the query performs the worst; 3) even when we destroy the multi-turn
associations and single-turn semantics in the demos, increasing the number of
demos still improves dialogue performance, proving that LLMs can learn from
corrupted dialogue demos. Previous explanations of the ICL mechanism, such as
\\(n\\)-gram induction head, cannot fully account for this phenomenon.
