---
layout: publication
title: 'Chatllm Network: More Brains, More Intelligence'
authors: Rui Hao, Linmei Hu, Weijian Qi, Qingliu Wu, Yirui Zhang, Liqiang Nie
conference: "Arxiv"
year: 2023
bibkey: hao2023chatllm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.12998"}
tags: ['Prompting', 'Model Architecture', 'GPT']
---
Dialogue-based language models mark a huge milestone in the field of
artificial intelligence, by their impressive ability to interact with users, as
well as a series of challenging tasks prompted by customized instructions.
However, the prevalent large-scale dialogue-based language models like ChatGPT
still have room for improvement, such as unstable responses to questions and
the inability to think cooperatively like humans. Considering the ability of
dialogue-based language models in conversation and their inherent randomness in
thinking, we propose ChatLLM network that allows multiple dialogue-based
language models to interact, provide feedback, and think together. We design
the network of ChatLLMs based on ChatGPT. Specifically, individual instances of
ChatGPT may possess distinct perspectives towards the same problem, and by
consolidating these diverse viewpoints via a separate ChatGPT, the ChatLLM
network system can conduct decision-making more objectively and
comprehensively. In addition, a language-based feedback mechanism comparable to
backpropagation is devised to update the ChatGPTs within the network.
Experiments on two datasets demonstrate that our network attains significant
improvements in problem-solving, leading to observable progress amongst each
member.
