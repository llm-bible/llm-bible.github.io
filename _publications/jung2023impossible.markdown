---
layout: publication
title: Impossible Distillation From Low45;quality Model To High45;quality Dataset amp; Model For Summarization And Paraphrasing
authors: Jung Jaehun, West Peter, Jiang Liwei, Brahman Faeze, Lu Ximing, Fisher Jillian, Sorensen Taylor, Choi Yejin
conference: "Arxiv"
year: 2023
bibkey: jung2023impossible
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.16635"}
tags: ['Applications', 'Distillation', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Tools']
---
We present Impossible Distillation a novel framework for paraphrasing and sentence summarization that distills a high45;quality dataset and model from a low45;quality teacher that itself cannot perform these tasks. Unlike prior works that rely on an extreme45;scale teacher model (e.g. GPT3) or task45;specific architecture we hypothesize and verify the paraphrastic proximity intrinsic to pre45;trained LMs (e.g. GPT2) where paraphrases occupy a proximal subspace in the LM distribution. By identifying and distilling generations from these subspaces Impossible Distillation produces a high45;quality dataset and model even from GPT245;scale LMs. We evaluate our method on multiple benchmarks spanning unconstrained / syntax45;controlled paraphrase generation and sentence summarization. Our model with 770M parameters consistently outperforms strong baselines including models distilled from ChatGPT and sometimes even ChatGPT itself. Also we find that our distilled dataset from 1.5B LMs exhibits higher diversity and fidelity than up to 13 times larger datasets.
