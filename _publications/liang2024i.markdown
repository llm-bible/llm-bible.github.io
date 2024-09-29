---
layout: publication
title: I45;SHEEP Self45;alignment Of LLM From Scratch Through An Iterative Self45;enhancement Paradigm
authors: Liang Yiming, Zhang Ge, Qu Xingwei, Zheng Tianyu, Guo Jiawei, Du Xinrun, Yang Zhenzhu, Liu Jiaheng, Lin Chenghua, Ma Lei, Huang Wenhao, Zhang Jiajun
conference: "Arxiv"
year: 2024
bibkey: liang2024i
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.08072"}
  - {name: "Code", url: "https://anonymous.4open.science/r/I&#45;SHEEP&#125;"}
tags: ['Applications', 'Has Code', 'RAG']
---
Large Language Models (LLMs) have achieved significant advancements however the common learning paradigm treats LLMs as passive information repositories neglecting their potential for active learning and alignment. Some approaches train LLMs using their own generated synthetic data exploring the possibility of active alignment. However there is still a huge gap between these one45;time alignment methods and the continuous automatic alignment of humans. In this paper we introduce textbf123;I45;SHEEP125; an textbf123;I125;terative textbf123;S125;elf45;Entextbf123;H125;anctextbf123;E125;mtextbf123;E125;nt textbf123;P125;aradigm.This human45;like paradigm enables LLMs to textbf123;continuously self45;align from scratch with nothing125;. Compared to the one45;time alignment method Dromedary cite123;sun2023principledriven125; which refers to the first iteration in this paper I45;SHEEP can significantly enhance capacities on both Qwen and Llama models. I45;SHEEP achieves a maximum relative improvement of 78.237; in the Alpaca Eval 24.037; in the MT Bench and an absolute increase of 8.8837; in the IFEval accuracy over subsequent iterations in Qwen45;1.5 72B model. Additionally I45;SHEEP surpasses the base model in various standard benchmark generation tasks achieving an average improvement of 24.7737; in code generation tasks 12.0437; in TrivialQA and 20.2937; in SQuAD. We also provide new insights based on the experiment results. Our codes datasets and models are available at textbf123;https://anonymous.4open.science/r/I&#45;SHEEP&#125;.
