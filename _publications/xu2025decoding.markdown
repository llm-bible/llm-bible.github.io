---
layout: publication
title: 'Decoding Recommendation Behaviors Of In-context Learning Llms Through Gradient Descent'
authors: Yi Xu, Weicong Qin, Weijie Yu, Ming He, Jianping Fan, Jun Xu
conference: "Arxiv"
year: 2025
bibkey: xu2025decoding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.04386"}
tags: ['Security', 'Training Techniques', 'Efficiency and Optimization', 'Reinforcement Learning', 'RAG', 'RecSys', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'In-Context Learning']
---
Recently, there has been a growing trend in utilizing large language models
(LLMs) for recommender systems, referred to as LLMRec. A notable approach
within this trend is not to fine-tune these models directly but instead to
leverage In-Context Learning (ICL) methods tailored for LLMRec, denoted as
LLM-ICL Rec. Many contemporary techniques focus on harnessing ICL content to
enhance LLMRec performance.
  However, optimizing LLMRec with ICL content presents unresolved challenges.
Specifically, two key issues stand out: (1) the limited understanding of why
using a few demonstrations without model fine-tuning can lead to better
performance compared to zero-shot recommendations. (2) the lack of evaluation
metrics for demonstrations in LLM-ICL Rec and the absence of the theoretical
analysis and practical design for optimizing the generation of ICL content for
recommendation contexts.
  To address these two main issues, we propose a theoretical model, the LLM-ICL
Recommendation Equivalent Gradient Descent model (LRGD) in this paper, which
connects recommendation generation with gradient descent dynamics. We
demonstrate that the ICL inference process in LLM aligns with the training
procedure of its dual model, producing token predictions equivalent to the dual
model's testing outputs. Building on these theoretical insights, we propose an
evaluation metric for assessing demonstration quality. We integrate
perturbations and regularizations in LRGD to enhance the robustness of the
recommender system. To further improve demonstration effectiveness, prevent
performance collapse, and ensure long-term adaptability, we also propose a
two-stage optimization process in practice. Extensive experiments and detailed
analysis on three Amazon datasets validate the theoretical equivalence and
support the effectiveness of our theoretical analysis and practical module
design.
