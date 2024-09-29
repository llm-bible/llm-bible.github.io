---
layout: publication
title: Large Language Models Are Temporal And Causal Reasoners For Video Question Answering
authors: Ko Dohwan, Lee Ji Soo, Kang Wooyoung, Roh Byungseok, Kim Hyunwoo J.
conference: "Arxiv"
year: 2023
bibkey: ko2023large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.15747"}
  - {name: "Code", url: "https://github.com/mlvlab/Flipped&#45;VQA"}
tags: ['Applications', 'Ethics And Bias', 'GPT', 'Has Code', 'Model Architecture', 'RAG', 'Tools']
---
Large Language Models (LLMs) have shown remarkable performances on a wide range of natural language understanding and generation tasks. We observe that the LLMs provide effective priors in exploiting textit123;linguistic shortcuts125; for temporal and causal reasoning in Video Question Answering (VideoQA). However such priors often cause suboptimal results on VideoQA by leading the model to over45;rely on questions textit123;i.e.125; textit123;linguistic bias125; while ignoring visual content. This is also known as ungrounded guesses or hallucinations. To address this problem while leveraging LLMs prior on VideoQA we propose a novel framework Flipped45;VQA encouraging the model to predict all the combinations of langleV Q Arangle triplet by flipping the source pair and the target label to understand their complex relationships textit123;i.e.125; predict A Q and V given a VQ VA and QA pairs respectively. In this paper we develop LLaMA45;VQA by applying Flipped45;VQA to LLaMA and it outperforms both LLMs45;based and non45;LLMs45;based models on five challenging VideoQA benchmarks. Furthermore our Flipped45;VQA is a general framework that is applicable to various LLMs (OPT and GPT45;J) and consistently improves their performances. We empirically demonstrate that Flipped45;VQA not only enhances the exploitation of linguistic shortcuts but also mitigates the linguistic bias which causes incorrect answers over45;relying on the question. Code is available at https://github.com/mlvlab/Flipped&#45;VQA.
