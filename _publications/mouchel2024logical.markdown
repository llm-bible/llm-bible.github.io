---
layout: publication
title: 'A Logical Fallacy-informed Framework For Argument Generation'
authors: Mouchel Luca, Paul Debjit, Cui Shaobo, West Robert, Bosselut Antoine, Faltings Boi
conference: "Arxiv"
year: 2024
bibkey: mouchel2024logical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.03618"}
tags: ['Efficiency And Optimization', 'RAG', 'Reinforcement Learning', 'Tools']
---
Despite the remarkable performance of Large Language Models (LLMs), they
still struggle with generating logically sound arguments, resulting in
potential risks such as spreading misinformation. An important factor
contributing to LLMs' suboptimal performance in generating coherent arguments
is their oversight of logical fallacies. To address this issue, we introduce
FIPO, a fallacy-informed framework that leverages preference optimization
methods to steer LLMs toward logically sound arguments. FIPO includes a
classification loss, to capture the fine-grained information on fallacy
categories. Our results on argumentation datasets show that our method reduces
the fallacy errors by up to 17.5%. Furthermore, our human evaluation results
indicate that the quality of the generated arguments by our method
significantly outperforms the fine-tuned baselines, as well as prior preference
optimization methods, such as DPO. These findings highlight the importance of
ensuring models are aware of logical fallacies for effective argument
generation.
