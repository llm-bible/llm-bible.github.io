---
layout: publication
title: 'Beyond Imitation: Learning Key Reasoning Steps From Dual Chain-of-thoughts In Reasoning Distillation'
authors: Chengwei Dai, Kun Li, Wei Zhou, Songlin Hu
conference: "Arxiv"
year: 2024
bibkey: dai2024beyond
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.19737"}
  - {name: "Code", url: "https://github.com/C-W-D/EDIT"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Pretraining Methods', 'Prompting', 'Distillation']
---
As Large Language Models (LLMs) scale up and gain powerful Chain-of-Thoughts
(CoTs) reasoning abilities, practical resource constraints drive efforts to
distill these capabilities into more compact Smaller Language Models (SLMs). We
find that CoTs consist mainly of simple reasoning forms, with a small
proportion (\\(\approx 4.7%\\)) of key reasoning steps that truly impact
conclusions. However, previous distillation methods typically involve
supervised fine-tuning student SLMs only on correct CoTs data produced by
teacher LLMs, resulting in students struggling to learn the key reasoning
steps, instead imitating the teacher's reasoning forms and making errors or
omissions on these steps. To address these issues, drawing an analogy to human
learning, where analyzing mistakes according to correct solutions often reveals
the crucial steps leading to successes or failures, we propose
mistak\textbf\{E\}-\textbf\{D\}riven key reason\textbf\{I\}ng step
distilla\textbf\{T\}ion (\textbf\{EDIT\}), a novel method that further aids SLMs
learning key reasoning steps rather than mere simple fine-tuning. Firstly, to
expose these crucial steps in CoTs, we design specific prompts to generate dual
CoTs data with similar reasoning paths but divergent conclusions. Then, we
apply the minimum edit distance algorithm on the dual CoTs data to locate these
key steps and optimize the likelihood of these steps. Extensive experiments
validate the effectiveness of EDIT across both in-domain and out-of-domain
benchmark reasoning datasets. Further analysis shows that EDIT can generate
high-quality CoTs with more correct key reasoning steps. Notably, we also
explore how different mistake patterns affect performance and find that EDIT
benefits more from logical errors than from knowledge or mathematical
calculation errors in dual CoTs\footnote\{Code can be found at
\url\{https://github.com/C-W-D/EDIT\}\}.
