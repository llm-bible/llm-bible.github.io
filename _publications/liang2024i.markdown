---
layout: publication
title: I-SHEEP&#58; Self-alignment Of LLM From Scratch Through An Iterative Self-enhancement Paradigm
authors: Liang Yiming, Zhang Ge, Qu Xingwei, Zheng Tianyu, Guo Jiawei, Du Xinrun, Yang Zhenzhu, Liu Jiaheng, Lin Chenghua, Ma Lei, Huang Wenhao, Zhang Jiajun
conference: "Arxiv"
year: 2024
bibkey: liang2024i
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.08072"}
  - {name: "Code", url: "https://anonymous.4open.science/r/I-SHEEP"}
tags: ['Applications', 'Has Code', 'RAG']
---
Large Language Models (LLMs) have achieved significant advancements however the common learning paradigm treats LLMs as passive information repositories neglecting their potential for active learning and alignment. Some approaches train LLMs using their own generated synthetic data exploring the possibility of active alignment. However there is still a huge gap between these one-time alignment methods and the continuous automatic alignment of humans. In this paper we introduce (textbf)I-SHEEP an (textbfI)terative (textbfS)elf-En(textbfH)anc(textbfE)m(textbfE)nt (textbfP)aradigm.This human-like paradigm enables LLMs to (textbf)continuously self-align from scratch with nothing. Compared to the one-time alignment method Dromedary (citesun2023principledriven) which refers to the first iteration in this paper I-SHEEP can significantly enhance capacities on both Qwen and Llama models. I-SHEEP achieves a maximum relative improvement of 78.237; in the Alpaca Eval 24.037; in the MT Bench and an absolute increase of 8.8837; in the IFEval accuracy over subsequent iterations in Qwen-1.5 72B model. Additionally I-SHEEP surpasses the base model in various standard benchmark generation tasks achieving an average improvement of 24.7737; in code generation tasks 12.0437; in TrivialQA and 20.2937; in SQuAD. We also provide new insights based on the experiment results. Our codes datasets and models are available at (textbf)https://anonymous.4open.science/r/I-SHEEP\}."
