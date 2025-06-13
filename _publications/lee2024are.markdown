---
layout: publication
title: 'Are Llm-judges Robust To Expressions Of Uncertainty? Investigating The Effect Of Epistemic Markers On Llm-based Evaluation'
authors: Dongryeol Lee, Yerin Hwang, Yongil Kim, Joonsuk Park, Kyomin Jung
conference: "Arxiv"
year: 2024
bibkey: lee2024are
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.20774"}
tags: ['Security', 'Model Architecture', 'Reinforcement Learning', 'GPT', 'Ethics and Bias']
---
In line with the principle of honesty, there has been a growing effort to
train large language models (LLMs) to generate outputs containing epistemic
markers. However, evaluation in the presence of epistemic markers has been
largely overlooked, raising a critical question: Could the use of epistemic
markers in LLM-generated outputs lead to unintended negative consequences? To
address this, we present EMBER, a benchmark designed to assess the robustness
of LLM-judges to epistemic markers in both single and pairwise evaluation
settings. Our findings, based on evaluations using EMBER, reveal that all
tested LLM-judges, including GPT-4o, show a notable lack of robustness in the
presence of epistemic markers. Specifically, we observe a negative bias toward
epistemic markers, with a stronger bias against markers expressing uncertainty.
This suggests that LLM-judges are influenced by the presence of these markers
and do not focus solely on the correctness of the content.
