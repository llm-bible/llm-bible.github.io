---
layout: publication
title: 'A Logical Fallacy-informed Framework For Argument Generation'
authors: Luca Mouchel, Debjit Paul, Shaobo Cui, Robert West, Antoine Bosselut, Boi Faltings
conference: "Arxiv"
year: 2024
bibkey: mouchel2024logical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.03618"}
tags: ['Efficiency and Optimization', 'RAG', 'Tools', 'Reinforcement Learning']
---
Despite the remarkable performance of Large Language Models (LLMs) in natural
language processing tasks, they still struggle with generating logically sound
arguments, resulting in potential risks such as spreading misinformation. To
address this issue, we introduce FIPO, a fallacy-informed framework that
leverages preference optimization methods to steer LLMs toward logically sound
arguments. FIPO includes a classification loss, to capture the fine-grained
information on fallacy types. Our results on argumentation datasets show that
our method reduces the fallacy errors by up to 17.5%. Furthermore, our human
evaluation results indicate that the quality of the generated arguments by our
method significantly outperforms the fine-tuned baselines, as well as other
preference optimization methods, such as DPO. These findings highlight the
importance of ensuring models are aware of logical fallacies for effective
argument generation. Our code is available at
github.com/lucamouchel/Logical-Fallacies.
