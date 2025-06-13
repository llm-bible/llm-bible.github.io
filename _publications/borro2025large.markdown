---
layout: publication
title: 'Large Language Models As Common-sense Heuristics'
authors: Andrey Borro, Patricia J Riddle, Michael W Barley, Michael J Witbrock
conference: "Arxiv"
year: 2025
bibkey: borro2025large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.18816"}
tags: ['Prompting', 'RAG']
---
While systems designed for solving planning tasks vastly outperform Large
Language Models (LLMs) in this domain, they usually discard the rich semantic
information embedded within task descriptions. In contrast, LLMs possess
parametrised knowledge across a wide range of topics, enabling them to leverage
the natural language descriptions of planning tasks in their solutions.
However, current research in this direction faces challenges in generating
correct and executable plans. Furthermore, these approaches depend on the LLM
to output solutions in an intermediate language, which must be translated into
the representation language of the planning task. We introduce a novel planning
method, which leverages the parametrised knowledge of LLMs by using their
output as a heuristic for Hill-Climbing Search. This approach is further
enhanced by prompting the LLM to generate a solution estimate to guide the
search. Our method outperforms the task success rate of similar systems within
a common household environment by 22 percentage points, with consistently
executable plans. All actions are encoded in their original representation,
demonstrating that strong results can be achieved without an intermediate
language, thus eliminating the need for a translation step.
