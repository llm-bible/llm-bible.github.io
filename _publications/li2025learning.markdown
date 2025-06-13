---
layout: publication
title: 'R3-RAG: Learning Step-by-step Reasoning And Retrieval For Llms Via Reinforcement Learning'
authors: Yuan Li, Qi Luo, Xiaonan Li, Bufan Li, Qinyuan Cheng, Bo Wang, Yining Zheng, Yuxin Wang, Zhangyue Yin, Xipeng Qiu
conference: "Arxiv"
year: 2025
bibkey: li2025learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.23794"}
  - {name: "Code", url: "https://github.com/Yuan-Li-FNLP/R3-RAG"}
tags: ['Agentic', 'RAG', 'Reinforcement Learning', 'Has Code', 'Prompting']
---
Retrieval-Augmented Generation (RAG) integrates external knowledge with Large Language Models (LLMs) to enhance factual correctness and mitigate hallucination. However, dense retrievers often become the bottleneck of RAG systems due to their limited parameters compared to LLMs and their inability to perform step-by-step reasoning. While prompt-based iterative RAG attempts to address these limitations, it is constrained by human-designed workflows. To address these limitations, we propose \\(\textbf\{R3-RAG\}\\), which uses \\(\textbf\{R\}\\)einforcement learning to make the LLM learn how to \\(\textbf\{R\}\\)eason and \\(\textbf\{R\}\\)etrieve step by step, thus retrieving comprehensive external knowledge and leading to correct answers. R3-RAG is divided into two stages. We first use cold start to make the model learn the manner of iteratively interleaving reasoning and retrieval. Then we use reinforcement learning to further harness its ability to better explore the external retrieval environment. Specifically, we propose two rewards for R3-RAG: 1) answer correctness for outcome reward, which judges whether the trajectory leads to a correct answer; 2) relevance-based document verification for process reward, encouraging the model to retrieve documents that are relevant to the user question, through which we can let the model learn how to iteratively reason and retrieve relevant documents to get the correct answer. Experimental results show that R3-RAG significantly outperforms baselines and can transfer well to different retrievers. We release R3-RAG at https://github.com/Yuan-Li-FNLP/R3-RAG.
