---
layout: publication
title: 'Large Language Models Are Parallel Multilingual Learners'
authors: Mu Yongyu, Feng Peinan, Cao Zhiquan, Wu Yuzhang, Li Bei, Wang Chenglong, Xiao Tong, Song Kai, Liu Tongran, Zhang Chunliang, Zhu Jingbo
conference: "Arxiv"
year: 2024
bibkey: mu2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.09073"}
tags: ['Efficiency And Optimization', 'In Context Learning', 'Prompting', 'Pruning', 'RAG']
---
In this study, we reveal an in-context learning (ICL) capability of multilingual large language models (LLMs): by translating the input to several languages, we provide Parallel Input in Multiple Languages (PiM) to LLMs, which significantly enhances their comprehension abilities. To test this capability, we design extensive experiments encompassing 8 typical datasets, 7 languages and 8 state-of-the-art multilingual LLMs. Experimental results show that (1) incorporating more languages help PiM surpass the conventional ICL further; (2) even combining with the translations that are inferior to baseline performance can also help. Moreover, by examining the activated neurons in LLMs, we discover a counterintuitive but interesting phenomenon. Contrary to the common thought that PiM would activate more neurons than monolingual input to leverage knowledge learned from diverse languages, PiM actually inhibits neurons and promotes more precise neuron activation especially when more languages are added. This phenomenon aligns with the neuroscience insight about synaptic pruning, which removes less used neural connections, strengthens remainders, and then enhances brain intelligence.
