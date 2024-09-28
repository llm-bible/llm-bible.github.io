---
layout: publication
title: Retrieving Supporting Evidence for LLMs Generated Answers
authors: Huo Siqing, Arabzadeh Negar, Clarke Charles L. A.
conference: "Arxiv"
year: 2023
bibkey: huo2023retrieving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.13781"}
tags: ['Applications', 'Arxiv']
---
Current large language models (LLMs) can exhibit near-human levels of performance on many natural language tasks including open-domain question answering. Unfortunately they also convincingly hallucinate incorrect answers so that responses to questions must be verified against external sources before they can be accepted at face value. In this paper we report a simple experiment to automatically verify generated answers against a corpus. After presenting a question to an LLM and receiving a generated answer we query the corpus with the combination of the question + generated answer. We then present the LLM with the combination of the question + generated answer + retrieved answer prompting it to indicate if the generated answer can be supported by the retrieved answer. We base our experiment on questions and passages from the MS MARCO (V1) test collection exploring three retrieval approaches ranging from standard BM25 to a full question answering stack including a reader based on the LLM. For a large fraction of questions we find that an LLM is capable of verifying its generated answer if appropriate supporting material is provided. However with an accuracy of 70-80 this approach cannot be fully relied upon to detect hallucinations.
