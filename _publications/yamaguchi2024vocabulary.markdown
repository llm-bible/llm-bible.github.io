---
layout: publication
title: Vocabulary Expansion For Low45;resource Cross45;lingual Transfer
authors: Yamaguchi Atsuki, Villavicencio Aline, Aletras Nikolaos
conference: "Arxiv"
year: 2024
bibkey: yamaguchi2024vocabulary
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11477"}
tags: ['Efficiency And Optimization', 'Training Techniques']
---
Large language models (LLMs) have shown remarkable capabilities in many languages beyond English. Yet LLMs require more inference steps when generating non45;English text due to their reliance on English45;centric tokenizers vocabulary and pre45;training data resulting in higher usage costs to non45;English speakers. Vocabulary expansion with target language tokens is a widely used cross45;lingual vocabulary adaptation approach to remedy this issue. Despite its effectiveness in inference speedup the majority of previous work has focused on high45;resource settings assuming access to a substantial amount of target language data to effectively initialize the embeddings of the new tokens and adapt the LLM to the target language. However vocabulary expansion for LLMs in low45;resource settings (i.e. languages and compute) has yet to be explored. In this paper we investigate sample45;efficient adaptation strategies from different angles including target vocabulary size and initialization methods and the amount of target data available for adaptation. Extensive experiments across typologically diverse languages tasks and models show that simpler heuristic45;based embedding initialization is more efficient and robust to changes in target vocabulary size and adaptation data in low45;resource settings outperforming a popular random initialization and a more sophisticated state45;of45;the45;art approach that relies on external data and model.
