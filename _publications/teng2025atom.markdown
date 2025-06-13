---
layout: publication
title: 'Atom Of Thoughts For Markov LLM Test-time Scaling'
authors: Fengwei Teng, Zhaoyang Yu, Quan Shi, Jiayi Zhang, Chenglin Wu, Yuyu Luo
conference: "Arxiv"
year: 2025
bibkey: teng2025atom
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.12018"}
  - {name: "Code", url: "https://github.com/qixucen/atom}{https://github.com/qixucen/atom"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'GPT', 'Has Code']
---
Large Language Models (LLMs) achieve superior performance through
training-time scaling, and test-time scaling further enhances their
capabilities by conducting effective reasoning during inference. However, as
the scale of reasoning increases, existing test-time scaling methods suffer
from accumulated historical information, which not only wastes computational
resources but also interferes with effective reasoning. To address this issue,
we observe that complex reasoning can be achieved by solving a series of
independent and self-contained subquestions. These subquestions are essentially
\textit\{atomic questions\}, exhibiting the memoryless property similar to Markov
processes. Based on this observation, we propose Atom of Thoughts (\our), where
each state transition consists of decomposing the current question into a
dependency-based directed acyclic graph and contracting its subquestions,
forming a simplified question that maintains answer equivalence with the
original problem. This answer preservation enables the iterative
\textit\{decomposition-contraction\} process to naturally form a meaningful
Markov reasoning process. Furthermore, these atomic states can be seamlessly
integrated into existing test-time scaling methods, enabling \our to serve as a
plug-in enhancement for improving reasoning capabilities. Experiments across
six benchmarks demonstrate the effectiveness of \our both as a standalone
framework and a plug-in enhancement. Notably, on HotpotQA, when applied to
gpt-4o-mini, \our achieves an \textbf\{80.6%\} F1 score, surpassing o3-mini by
\textbf\{3.4%\} and DeepSeek-R1 by \textbf\{10.6%\}. The code is available at
\href\{https://github.com/qixucen/atom\}\{https://github.com/qixucen/atom\}.
