---
layout: publication
title: 'Strong And Efficient Baselines For Open Domain Conversational Question Answering'
authors: Coman Andrei C., Barlacchi Gianni, De Gispert Adrià
conference: "Arxiv"
year: 2023
bibkey: coman2023strong
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.14708"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'Merging', 'Model Architecture', 'RAG']
---
Unlike the Open Domain Question Answering (ODQA) setting, the conversational
(ODConvQA) domain has received limited attention when it comes to reevaluating
baselines for both efficiency and effectiveness. In this paper, we study the
State-of-the-Art (SotA) Dense Passage Retrieval (DPR) retriever and
Fusion-in-Decoder (FiD) reader pipeline, and show that it significantly
underperforms when applied to ODConvQA tasks due to various limitations. We
then propose and evaluate strong yet simple and efficient baselines, by
introducing a fast reranking component between the retriever and the reader,
and by performing targeted finetuning steps. Experiments on two ODConvQA tasks,
namely TopiOCQA and OR-QuAC, show that our method improves the SotA results,
while reducing reader's latency by 60%. Finally, we provide new and valuable
insights into the development of challenging baselines that serve as a
reference for future, more intricate approaches, including those that leverage
Large Language Models (LLMs).
