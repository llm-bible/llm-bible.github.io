---
layout: publication
title: 'Ligt: Layout-infused Generative Transformer For Visual Question Answering On Vietnamese Receipts'
authors: Thanh-phong Le, Trung Le Chi Phan, Nghia Hieu Nguyen, Kiet Van Nguyen
conference: "Arxiv"
year: 2025
bibkey: le2025layout
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.19202"}
tags: ['Transformer', 'Applications', 'RAG', 'Model Architecture', 'Pretraining Methods', 'Multimodal Models']
---
Document Visual Question Answering (Document VQA) challenges multimodal
systems to holistically handle textual, layout, and visual modalities to
provide appropriate answers. Document VQA has gained popularity in recent years
due to the increasing amount of documents and the high demand for digitization.
Nonetheless, most of document VQA datasets are developed in high-resource
languages such as English. In this paper, we present ReceiptVQA
(\textbf\{Receipt\} \textbf\{V\}isual \textbf\{Q\}uestion \textbf\{A\}nswering), the
initial large-scale document VQA dataset in Vietnamese dedicated to receipts, a
document kind with high commercial potentials. The dataset encompasses
\textbf\{9,000+\} receipt images and \textbf\{60,000+\} manually annotated
question-answer pairs. In addition to our study, we introduce LiGT
(\textbf\{L\}ayout-\textbf\{i\}nfused \textbf\{G\}enerative \textbf\{T\}ransformer), a
layout-aware encoder-decoder architecture designed to leverage embedding layers
of language models to operate layout embeddings, minimizing the use of
additional neural modules. Experiments on ReceiptVQA show that our architecture
yielded promising performance, achieving competitive results compared with
outstanding baselines. Furthermore, throughout analyzing experimental results,
we found evident patterns that employing encoder-only model architectures has
considerable disadvantages in comparison to architectures that can generate
answers. We also observed that it is necessary to combine multiple modalities
to tackle our dataset, despite the critical role of semantic understanding from
language models. We hope that our work will encourage and facilitate future
development in Vietnamese document VQA, contributing to a diverse multimodal
research community in the Vietnamese language.
