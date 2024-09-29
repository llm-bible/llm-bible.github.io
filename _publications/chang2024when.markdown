---
layout: publication
title: When Parts Are Greater Than Sums Individual LLM Components Can Outperform Full Models
authors: Chang Ting-yun, Thomason Jesse, Jia Robin
conference: "Arxiv"
year: 2024
bibkey: chang2024when
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.13131"}
tags: ['Attention Mechanism', 'Ethics And Bias', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning']
---
This paper studies in45;context learning (ICL) by decomposing the output of large language models into the individual contributions of attention heads and MLPs (components). We observe curious components good45;performing ones that individually do well on a classification task even when the model performs poorly; bad45;performing ones that do much worse than chance; and label45;biased components that always predict the same label. We find that component accuracies are well45;correlated across different demonstration sets and perturbations of prompt templates even when the full45;model accuracy varies greatly. Based on our findings we propose component reweighting which learns to linearly re45;scale the component activations from a few labeled examples. Given 24 labeled examples our method improves by an average of 6.037; accuracy points over 2445;shot ICL across 8 tasks on Llama45;245;7B. Overall this paper both enriches our understanding of ICL and provides a practical method for improvement by examining model internals.
