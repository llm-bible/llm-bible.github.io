---
layout: publication
title: Personalized Abstractive Summarization By Tri-agent Generation Pipeline
authors: Xiao Wen, Xie Yujia, Carenini Giuseppe, He Pengcheng
conference: "Arxiv"
year: 2023
bibkey: xiao2023personalized
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.02483"}
  - {name: "Code", url: "https://github.com/Wendy-Xiao/chatgpt_editing_summ"}
tags: ['Agentic', 'Applications', 'GPT', 'Has Code', 'Model Architecture', 'RAG', 'Reinforcement Learning']
---
Tailoring outputs from large language models like ChatGPT to implicit user preferences remains a challenge despite their impressive generative capabilities. In this paper we propose a tri-agent generation pipeline comprising a generator an instructor and an editor to enhance output personalization. The generator produces an initial output the instructor automatically generates editing instructions based on user preferences and the editor refines the output to align with those preferences. The inference-only large language model (ChatGPT) serves as both the generator and editor with a smaller model acting as the instructor to guide output generation. We train the instructor using editor-steered reinforcement learning leveraging feedback from a large-scale editor model to optimize instruction generation. Experimental results on two abstractive summarization datasets demonstrate the effectiveness of our approach in generating outputs that better meet user expectations. Code is available at (url)https://github.com/Wendy-Xiao/chatgpt\_editing\_summ\}"
