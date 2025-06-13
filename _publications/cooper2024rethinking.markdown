---
layout: publication
title: 'Rethinking Vlms And Llms For Image Classification'
authors: Avi Cooper, Keizo Kato, Chia-hsien Shih, Hiroaki Yamane, Kasper Vinken, Kentaro Takemoto, Taro Sunagawa, Hao-wei Yeh, Jin Yamanaka, Ian Mason, Xavier Boix
conference: "Arxiv"
year: 2024
bibkey: cooper2024rethinking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.14690"}
tags: ['GPT', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Prompting']
---
Visual Language Models (VLMs) are now increasingly being merged with Large
Language Models (LLMs) to enable new capabilities, particularly in terms of
improved interactivity and open-ended responsiveness. While these are
remarkable capabilities, the contribution of LLMs to enhancing the longstanding
key problem of classifying an image among a set of choices remains unclear.
Through extensive experiments involving seven models, ten visual understanding
datasets, and multiple prompt variations per dataset, we find that, for object
and scene recognition, VLMs that do not leverage LLMs can achieve better
performance than VLMs that do. Yet at the same time, leveraging LLMs can
improve performance on tasks requiring reasoning and outside knowledge. In
response to these challenges, we propose a pragmatic solution: a lightweight
fix involving a relatively small LLM that efficiently routes visual tasks to
the most suitable model for the task. The LLM router undergoes training using a
dataset constructed from more than 2.5 million examples of pairs of visual task
and model accuracy. Our results reveal that this lightweight fix surpasses or
matches the accuracy of state-of-the-art alternatives, including GPT-4V and
HuggingGPT, while improving cost-effectiveness.
