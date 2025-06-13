---
layout: publication
title: 'Data-prep-kit: Getting Your Data Ready For LLM Application Development'
authors: David Wood, Boris Lublinsky, Alexy Roytman, Shivdeep Singh, Constantin Adam, Abdulhamid Adebayo, Sungeun An, Yuan Chi Chang, Xuan-hong Dang, Nirmit Desai, Michele Dolfi, Hajar Emami-gohari, Revital Eres, Takuya Goto, Dhiraj Joshi, Yan Koyfman, Mohammad Nassar, Hima Patel, Paramesvaran Selvam, Yousaf Shah, Saptha Surendran, Daiki Tsuzuku, Petros Zerfos, Shahrokh Daijavad
conference: "Arxiv"
year: 2024
bibkey: wood2024data
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.18164'}
tags: ['Reinforcement Learning', 'RAG', 'Model Architecture']
---
Data preparation is the first and a very important step towards any Large
Language Model (LLM) development. This paper introduces an easy-to-use,
extensible, and scale-flexible open-source data preparation toolkit called Data
Prep Kit (DPK). DPK is architected and designed to enable users to scale their
data preparation to their needs. With DPK they can prepare data on a local
machine or effortlessly scale to run on a cluster with thousands of CPU Cores.
DPK comes with a highly scalable, yet extensible set of modules that transform
natural language and code data. If the user needs additional transforms, they
can be easily developed using extensive DPK support for transform creation.
These modules can be used independently or pipelined to perform a series of
operations. In this paper, we describe DPK architecture and show its
performance from a small scale to a very large number of CPUs. The modules from
DPK have been used for the preparation of Granite Models [1] [2]. We believe
DPK is a valuable contribution to the AI community to easily prepare data to
enhance the performance of their LLM models or to fine-tune models with
Retrieval-Augmented Generation (RAG).
