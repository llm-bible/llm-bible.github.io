---
layout: publication
title: 'Truthx: Alleviating Hallucinations By Editing Large Language Models In Truthful Space'
authors: Zhang Shaolei, Yu Tian, Feng Yang
conference: "Arxiv"
year: 2024
bibkey: zhang2024alleviating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.17811"}
tags: ['Pretraining Methods', 'RAG']
---
Large Language Models (LLMs) sometimes suffer from producing hallucinations especially LLMs may generate untruthful responses despite knowing the correct knowledge. Activating the truthfulness within LLM is the key to fully unlocking LLMs knowledge potential. In this paper we propose TruthX an inference-time intervention method to activate the truthfulness of LLM by identifying and editing the features within LLMs internal representations that govern the truthfulness. TruthX employs an auto-encoder to map LLMs representations into semantic and truthful latent spaces respectively and applies contrastive learning to identify a truthful editing direction within the truthful space. During inference by editing LLMs internal representations in truthful space TruthX effectively enhances the truthfulness of LLM. Experiments show that TruthX improves the truthfulness of 13 advanced LLMs by an average of 2037; on TruthfulQA benchmark. Further analyses suggest that TruthX can control LLM to produce truthful or hallucinatory responses via editing only one vector in LLMs internal representations.
