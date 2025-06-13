---
layout: publication
title: 'On The Effectiveness And Generalization Of Race Representations For Debiasing High-stakes Decisions'
authors: Dang Nguyen, Chenhao Tan
conference: "Arxiv"
year: 2025
bibkey: nguyen2025effectiveness
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.06303'}
tags: ['RAG', 'Fairness', 'Prompting', 'Bias Mitigation', 'Ethics and Bias']
---
Understanding and mitigating biases is critical for the adoption of large
language models (LLMs) in high-stakes decision-making. We introduce Admissions
and Hiring, decision tasks with hypothetical applicant profiles where a
person's race can be inferred from their name, as simplified test beds for
racial bias. We show that Gemma 2B Instruct and LLaMA 3.2 3B Instruct exhibit
strong biases. Gemma grants admission to 26% more White than Black applicants,
and LLaMA hires 60% more Asian than White applicants. We demonstrate that these
biases are resistant to prompt engineering: multiple prompting strategies all
fail to promote fairness. In contrast, using distributed alignment search, we
can identify "race subspaces" within model activations and intervene on them to
debias model decisions. Averaging the representation across all races within
the subspaces reduces Gemma's bias by 37-57%. Finally, we examine the
generalizability of Gemma's race subspaces, and find limited evidence for
generalization, where changing the prompt format can affect the race
representation. Our work suggests mechanistic approaches may provide a
promising venue for improving the fairness of LLMs, but a universal race
representation remains elusive.
