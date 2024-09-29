---
layout: publication
title: Personalized Abstractive Summarization By Tri45;agent Generation Pipeline
authors: Xiao Wen, Xie Yujia, Carenini Giuseppe, He Pengcheng
conference: "Arxiv"
year: 2023
bibkey: xiao2023personalized
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.02483"}
  - {name: "Code", url: "https://github.com/Wendy&#45;Xiao/chatgpt&#95;editing&#95;summ&#125;"}
tags: ['Agentic', 'Applications', 'GPT', 'Has Code', 'Model Architecture', 'RAG', 'Reinforcement Learning']
---
Tailoring outputs from large language models like ChatGPT to implicit user preferences remains a challenge despite their impressive generative capabilities. In this paper we propose a tri45;agent generation pipeline comprising a generator an instructor and an editor to enhance output personalization. The generator produces an initial output the instructor automatically generates editing instructions based on user preferences and the editor refines the output to align with those preferences. The inference45;only large language model (ChatGPT) serves as both the generator and editor with a smaller model acting as the instructor to guide output generation. We train the instructor using editor45;steered reinforcement learning leveraging feedback from a large45;scale editor model to optimize instruction generation. Experimental results on two abstractive summarization datasets demonstrate the effectiveness of our approach in generating outputs that better meet user expectations. Code is available at url123;https://github.com/Wendy&#45;Xiao/chatgpt&#95;editing&#95;summ&#125;
