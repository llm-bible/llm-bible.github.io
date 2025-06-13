---
layout: publication
title: 'Ruag: Learned-rule-augmented Generation For Large Language Models'
authors: Yudi Zhang, Pei Xiao, Lu Wang, Chaoyun Zhang, Meng Fang, Yali Du, Yevgeniy Puzyrev, Randolph Yao, Si Qin, Qingwei Lin, Mykola Pechenizkiy, Dongmei Zhang, Saravan Rajmohan, Qi Zhang
conference: "Arxiv"
year: 2024
bibkey: zhang2024learned
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.03349"}
tags: ['Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'In-Context Learning', 'Prompting', 'Attention Mechanism']
---
In-context learning (ICL) and Retrieval-Augmented Generation (RAG) have
gained attention for their ability to enhance LLMs' reasoning by incorporating
external knowledge but suffer from limited contextual window size, leading to
insufficient information injection. To this end, we propose a novel framework,
RuAG, to automatically distill large volumes of offline data into interpretable
first-order logic rules, which are injected into LLMs to boost their reasoning
capabilities. Our method begins by formulating the search process relying on
LLMs' commonsense, where LLMs automatically define head and body predicates.
Then, RuAG applies Monte Carlo Tree Search (MCTS) to address the combinational
searching space and efficiently discover logic rules from data. The resulting
logic rules are translated into natural language, allowing targeted knowledge
injection and seamless integration into LLM prompts for LLM's downstream task
reasoning. We evaluate our framework on public and private industrial tasks,
including natural language processing, time-series, decision-making, and
industrial tasks, demonstrating its effectiveness in enhancing LLM's capability
over diverse tasks.
