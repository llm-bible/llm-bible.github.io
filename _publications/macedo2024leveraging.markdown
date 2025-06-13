---
layout: publication
title: 'Intertrans: Leveraging Transitive Intermediate Translations To Enhance Llm-based Code Translation'
authors: Marcos Macedo, Yuan Tian, Pengyu Nie, Filipe R. Cogo, Bram Adams
conference: "Arxiv"
year: 2024
bibkey: macedo2024leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.01063"}
tags: ['RAG', 'Tools']
---
Code translation aims to convert a program from one programming language (PL)
to another. This long-standing software engineering task is crucial for
modernizing legacy systems, ensuring cross-platform compatibility, enhancing
performance, and more. However, automating this process remains challenging due
to many syntactic and semantic differences between PLs. Recent studies show
that even advanced techniques such as large language models (LLMs), especially
open-source LLMs, still struggle with the task. Currently, code LLMs are
trained with source code from multiple programming languages, thus presenting
multilingual capabilities.
  In this paper, we investigate whether such multilingual capabilities can be
harnessed to enhance code translation. To achieve this goal, we introduce
InterTrans, an LLM-based automated code translation approach that, in contrast
to existing approaches, leverages intermediate translations across PLs to
bridge the syntactic and semantic gaps between source and target PLs.
  InterTrans contains two stages. It first utilizes a novel Tree of Code
Translation (ToCT) algorithm to plan transitive intermediate translation
sequences between a given source and target PL, then validates them in a
specific order. We evaluate InterTrans with three open LLMs on three benchmarks
(i.e., CodeNet, HumanEval-X, and TransCoder) involving six PLs. Results show an
absolute improvement between 18.3% to 43.3% in Computation Accuracy (CA) for
InterTrans over Direct Translation with 10 attempts. The best-performing
variant of InterTrans (with Magicoder LLM) achieved an average CA of
87.3%-95.4% on three benchmarks.
