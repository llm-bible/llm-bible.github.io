---
layout: publication
title: Re2g Retrieve Rerank Generate
authors: Glass Michael, Rossiello Gaetano, Chowdhury Md Faisal Mahbub, Naik Ankita Rajaram, Cai Pengshan, Gliozzo Alfio
conference: "Arxiv"
year: 2022
bibkey: glass2022generate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2207.06300"}
  - {name: "Code", url: "https://github.com/IBM/kgi&#45;slot&#45;filling/tree/re2g"}
tags: ['Applications', 'Distillation', 'Efficiency And Optimization', 'GPT', 'Has Code', 'Merging', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Transformer']
---
As demonstrated by GPT45;3 and T5 transformers grow in capability as parameter spaces become larger and larger. However for tasks that require a large amount of knowledge non45;parametric memory allows models to grow dramatically with a sub45;linear increase in computational cost and GPU memory requirements. Recent models such as RAG and REALM have introduced retrieval into conditional generation. These models incorporate neural initial retrieval from a corpus of passages. We build on this line of research proposing Re2G which combines both neural initial retrieval and reranking into a BART45;based sequence45;to45;sequence generation. Our reranking approach also permits merging retrieval results from sources with incomparable scores enabling an ensemble of BM25 and neural initial retrieval. To train our system end45;to45;end we introduce a novel variation of knowledge distillation to train the initial retrieval reranker and generation using only ground truth on the target sequence output. We find large gains in four diverse tasks zero45;shot slot filling question answering fact45;checking and dialog with relative gains of 937; to 3437; over the previous state45;of45;the45;art on the KILT leaderboard. We make our code available as open source at https://github.com/IBM/kgi&#45;slot&#45;filling/tree/re2g.
